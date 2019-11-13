CHANGELOG

2019-08-29 - 0.8.0

    * Merged PR (https://github.com/justbetter/magento2-sentry/pull/24) thanks to https://github.com/kyriog
    * Merged PR (https://github.com/justbetter/magento2-sentry/pull/22) thanks to https://github.com/fredden
    * Merged PR (https://github.com/justbetter/magento2-sentry/pull/21) thanks to https://github.com/erikhansen
    
2019-06-19 - 0.7.2

    * Reverted async attribute

2019-06-19 - 0.7.1

    * Added async and crossorigin attribute to script tags

2019-04-23 - 0.7.0

    * Merged pull request avoiding magento crash (https://github.com/justbetter/magento2-sentry/pull/19)

2019-04-05 - 0.6.2

    * Fixed issues useing referenceBlock when adding scripts (https://github.com/justbetter/magento2-sentry/issues/18)

2019-02-14 - 0.6.1

    * Added missing files of PR 13 (https://github.com/justbetter/magento2-sentry/pull/16)

2019-02-14 - 0.6.0

    * Added Sentry script tag to catch javascript errors (https://github.com/justbetter/magento2-sentry/pull/13)

2019-02-13 - 0.5.1

    * Support for setting environment (https://github.com/justbetter/magento2-sentry/pull/12)

2018-12-07 - 0.5.0

    * Send extra parameters to sentry (https://github.com/justbetter/magento2-sentry/issues/11)
    * Added Magento 2.3.x support & dropped 2.1.x support
    * Fixed area code not set or already set

2018-10-17 - 0.4.2

    * Bugfix with area code already set - removed area code from constructor with causes problems at random cases. (https://github.com/justbetter/magento2-sentry/issues/10)
    * Removed info level - this log level is not useable in sentry.

2018-08-15 - 0.4.1

    * Removed plugin in di.xml to prevent fatal crash on storefrontend
    * Restored preference in di.xml

2018-08-10 - 0.4.0

    * Refactor of overwrite to plugin with monolog
    * Added user context
    * Added message context
    * Added extra magento store parameters
    * Refactor of ExceptionCatcher to use same SentryLogger
    * Bugfix area code not set
    * Refactor a lot of code
    * PSR2 compliance

2018-04-30 - 0.2.1

    * downgraded requirement monolog for magento 2.1.x

2018-04-30 - 0.2.0

    * Feature request to test sentry in development mode (https://github.com/justbetter/magento2-sentry/issues/4)
    * Added mage deploy mode to sentry in context_tags

2018-04-17 - 0.1.0

    * Feature request for sending test events (https://github.com/justbetter/magento2-sentry/issues/3)
    * Added ACL roles for editing sentry config

2018-03-25 - 0.0.6

    * Bugfix wrong file commit

2018-03-17 - 0.0.5

    * Initial commit module - basic working module
