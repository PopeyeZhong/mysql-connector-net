# Contributing Guidelines

We greatly appreciate feedback from our users, including bug reports and code contributions. Your input helps us improve, and we thank you for any issues you report or code you contribute.

## Reporting Issues

Before submitting a new bug report, please [check here](https://bugs.mysql.com/search.php) to see if the issue has already been reported.

When reporting a bug, ensure your report is as detailed as possible. Please include the following:

* Clear, reproducible steps to demonstrate the issue.
* Relevant platform and environment information.
* The specific version of the product in use.
* The version of the MySQL Server in use.
* Sample code that can help reproduce the issue, if applicable.

## Contributing Code

We welcome your code contributions. Before submitting code via a GitHub pull request or by filing a bug on [bugs.mysql.com](https://bugs.mysql.com), you will need to sign the Oracle Contributor Agreement (OCA). Instructions for signing the OCA are available on the [OCA Page](https://oca.opensource.oracle.com).

**Only pull requests from contributors who have signed the OCA can be accepted.**

### Submitting a Contribution

1. Ensure you have a user account at [bugs.mysql.com](https://bugs.mysql.com). You'll need to reference this account when submitting your OCA.
2. Sign the Oracle Contributor Agreement. Instructions are provided on the [OCA Page](https://oca.opensource.oracle.com).
3. Validate your contribution by including tests that adequately cover the functionality you're adding.
4. Ensure the entire test suite passes with your changes applied.
5. Submit your pull request through [GitHub](https://github.com/mysql/mysql-connector-net/pulls/) or upload it to a bug record on [bugs.mysql.com](https://bugs.mysql.com) using the _Contributions_ tab.

### Developing Your Pull Request

1. Create your pull request, following the [project's requirements](https://dev.mysql.com/doc/connector-net/en/connector-net-installation.html).
2. Include sufficient tests to validate the new functionality.
3. Confirm that the entire test suite passes with your changes applied.
4. Submit the pull request via [GitHub](https://github.com/mysql/mysql-connector-net/pulls/) or directly via [bugs.mysql.com](https://bugs.mysql.com).

We deeply value contributions to MySQL and thank you for supporting open-source development.

## Setting Up a Development Environment

You can use your preferred .NET IDE to view, edit, and compile the MySQL Connector/NET source code. For project configuration, please refer to the instructions in [Installing from Source](https://dev.mysql.com/doc/connector-net/en/connector-net-installation-source.html).

## Running Tests

Any code you contribute must pass our test suite. Each project has its own suite (e.g., *MySql.Data.Tests*). Be sure to run the entire test suite to ensure that no other functionality is affected by your changes. You can run the tests using your preferred IDE or via the CLI with the "dotnet" tool.

## Getting Help

If you need assistance or would like to reach out to the community, please use the following resources:

* [MySQL Connector/NET Developer Guide](https://dev.mysql.com/doc/connector-net/en/)
* [MySQL Connector/NET API](https://dev.mysql.com/doc/dev/connector-net/latest/)
* [MySQL NuGet](https://www.nuget.org/profiles/MySQL/)
* [MySQL Connector/NET and C#, Mono, .Net Forum](https://forums.mysql.com/list.php?38)
* [`#connectors` channel on MySQL Community Slack](https://mysqlcommunity.slack.com/messages/connectors/)  ([Sign-up](https://lefred.be/mysql-community-on-slack/) required if you do not have an Oracle account.)
* [@MySQL on X](https://x.com/MySQL/).
* [MySQL Blog](https://blogs.oracle.com/mysql/).
* [MySQL Connectors Blog archive](https://dev.mysql.com/blog-archive/?cat=Connectors%20%2F%20Languages).
* [MySQL Newsletter](https://www.mysql.com/news-and-events/newsletter/).
* [MySQL Bugs Tracking System](https://bugs.mysql.com).

We look forward to hearing from you and encourage you to get involved. Happy coding!

[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/MySQL?style=social)](https://x.com/intent/follow?screen_name=MySQL)
