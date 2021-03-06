# Summary

## Intro

* [Introduction](README.md)
  * [What's New With 5.0.0](intro/whats-new-with-500.md)
  * [What's New With 2.1.0](intro/whats-new-with-2.1.0.md)
  * [What's New With 2.0.0](intro/whats-new-with-2.0.0.md)
  * [About This Book](about-this-book.md)
  * [Author](author.md)

## Getting Started

* [Features at a Glance](need-for-logging/features-at-a-glance.md)
* [Installation](installation.md)
  * [LogBox Refcard](need-for-logging/logbox-refcard.md)
* [Need For Logging](need-for-logging/README.md)
* [How Does LogBox Work?](how-does-logbox-work/README.md)
  * [LogBox](how-does-logbox-work/logbox.md)
  * [Appender](how-does-logbox-work/appender.md)
  * [Logger](how-does-logbox-work/logger/README.md)
    * [Logger Category Inheritance](how-does-logbox-work/logger/logger-category-inheritance.md)
    * Security Levels
    * [Dynamic Appenders](how-does-logbox-work/logger/dynamic-appenders.md)
  * [Layout](how-does-logbox-work/layout.md)

## Configuration

* [Configuring LogBox](configuring-logbox/README.md)
  * [LogBox DSL](configuring-logbox/logbox-dsl.md)
  * [Adding Appenders](configuring-logbox/adding-appenders.md)
  * [Adding Categories to Specific Loggin Levels](configuring-logbox/adding-categories-to-specific-loggin-levels.md)
  * [Adding Categories Granularly](configuring-logbox/adding-categories-granularly.md)
  * [Configuring The Root Logger](configuring-logbox/configuring-the-root-logger.md)

## Usage

* [Using LogBox](using-logbox.md)
* [Using a Logger Object](using-a-logger-object/README.md)
  * [Can Methods For Performance](using-a-logger-object/can-methods-for-performance.md)
  * [$toString\(\) and ExtraInfo Argument](using-a-logger-object/usdtostring-and-extrainfo-argument.md)
* [Appender Properties](appender-properties/README.md)
  * [CFAppender](appender-properties/cfappender.md)
  * [ConsoleAppender](appender-properties/consoleappender.md)
  * [DBAppender](appender-properties/dbappender.md)
  * [EmailAppender](appender-properties/emailappender.md)
  * [FileAppender](appender-properties/fileappender.md)
  * [RollingFileAppender](appender-properties/rollingfileappender.md)
  * [ScopeAppender](appender-properties/scopeappender.md)
  * [SocketAppender](appender-properties/socketappender.md)
  * [TraceAppender](appender-properties/traceappender.md)
* [LogBox in a ColdBox Application](logbox-in-a-coldbox-application/README.md)
  * [Configuration Within ColdBox](logbox-in-a-coldbox-application/configuration-within-coldbox.md)
  * [Benefits of using LogBox in a ColdBox application](logbox-in-a-coldbox-application/benefits-of-using-logbox-in-a-coldbox-application.md)
  * [Where is LogBox stored in a ColdBox app?](logbox-in-a-coldbox-application/where-is-logbox-stored-in-a-coldbox-app.md)
  * [LogBox from the ColdBox Proxy](logbox-in-a-coldbox-application/logbox-from-the-coldbox-proxy.md)
  * [The LogBox Injection DSL](logbox-in-a-coldbox-application/the-logbox-injection-dsl.md)

## Extending LogBox

* [Creating Custom  Appenders](creating-custom-appenders/README.md)
  * [Helper Methods](creating-custom-appenders/helper-methods.md)
  * [Instance Members](creating-custom-appenders/instance-members.md)
  * [Dealing With Custom Layouts](creating-custom-appenders/dealing-with-custom-layouts.md)
  * [Registering Appenders at Runtime](creating-custom-appenders/registering-appenders-at-runtime.md)
* [Creating a Custom Layout](creating-a-custom-layout/README.md)
  * [Instance Members](creating-a-custom-layout/instance-members.md)

