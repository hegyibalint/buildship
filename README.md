# Eclipse Buildship: Gradle integration for the Eclipse IDE <a href="https://builds.gradle.org/viewType.html?buildTypeId=Tooling_Buildship_Checkpoint_Full_Test_Coverage_Phase_33"><img src="https://builds.gradle.org/guestAuth/app/rest/builds/buildType:(id:Tooling_Buildship_Checkpoint_Full_Test_Coverage_Phase_33)/statusIcon"/></a>

> [!NOTE]
> This is a forked repository that is adding [Declarative Gradle](https://declarative.gradle.org/) support to normal Buildship.
> In order to try out the features, follow the steps below:
>  1. Follow the [development guide](docs/development/README.md) to setup a local setup
>  1. Start a runtime Eclipse by using the "Launch Buildship" configuration
>  1. In the runtime Eclipse, go to the "Settings > Gradle > Experimental features" menu, and select the `lsp-all.jar` file (the file is the result of `shadowJar` assembled by [declarative-lsp](https://github.com/gradle/declarative-lsp), see that repository for further instructions)
>  1. Upon opening any `gradle.dcl` file, the LSP should turn on. Observe the console for any diagnostic messages.

Buildship is a set of Eclipse Plug-ins that provide a deep integration of Gradle into the Eclipse IDE. Buildship is hosted
on [eclipse.org](https://projects.eclipse.org/projects/tools.buildship).


## Requirements

Buildship can be used with Eclipse IDE 4.2.x or newer. Older versions of Eclipse the IDE might work but have not been tested explicitly. Depending
on the version of Gradle that Buildship interacts with, certain features of Buildship may not be available.


## Documentation

All documentation of Buildship for users and developers is hosted on [GitHub](https://github.com/eclipse/buildship).

More specifically, you can find

 * [User documentation](docs/user/README.md) (plugin installation, current functionality)
 * [Developer documentation](docs/development/README.md) (development environment setup)
 * [Build documentation](docs/pluginbuild/README.md) (building Eclipse projects with Gradle)
 * [Outline of upcoming stories](docs/stories/README.md)


## Discussions &amp; News

We are very interested in feedback from the Gradle and Eclipse communities. All things Buildship are discussed on the [Gradle Forums](http://discuss.gradle.org/c/help-discuss/buildship).


## Issue Tracking

Issues are tracked on GitHub. Add your :thumbsup: for issues that you care about to help us prioritize them. If you want to follow our priorities and progress, install the [ZenHub](https://www.zenhub.com/extension) extension and have a look at our [board](https://github.com/eclipse/buildship#boards).

## License

Buildship is available under the Eclipse Public License, Version 1.0.
