# awesome-azure-devops
a curated list of awesome resource for azure devops

[![update github pages](https://github.com/martcus/awesome-azure-devops/actions/workflows/update.gh.pages.yml/badge.svg)](https://github.com/martcus/awesome-azure-devops/actions/workflows/update.gh.pages.yml)

## table of contents

* [contributing](#contributing)
* [boards](#boards)
* [pipelines](#pipelines)
* [repos](#repos)
* [test plans](#test-plans)
* [artifacts](#artifacts)
* [extensions](#extensions)
* [widget](#widget)
* [others](#others)

## contributing
your contributions are welcomed!
some notes for your help:
* check out the the _[markdown syntax](https://guides.github.com/features/mastering-markdown/) guide_
* all text must be in _lowercase_
* add link in _alphabetical order_
* every link follow the syntax: _name of the resource - brief description_
* send a _pull request_ to contribute

## boards
* [overview](https://azure.microsoft.com/en-us/services/devops/boards) - plan, track, and discuss work across teams. define and update issues, bugs, user stories, & other work with customizable scrum, kanban, and agile tools.
* [documentation](https://docs.microsoft.com/en-us/azure/devops/boards/index?view=azdevops) - azure boards documentation

## pipelines
* [overview](https://azure.microsoft.com/en-us/services/devops/pipelines/) - implement continuous integration and continuous delivery (ci/cd) for the app and platform of your choice
* [documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/index?view=azdevops) - azure pipelines documentation
  * [conditions](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/conditions?view=azure-devops&tabs=yaml) - you can specify the conditions under which each stage, job, or step runs
  * [expressions](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/expressions?view=azure-devops) - expressions can be used in many places where you need to specify a string, boolean, or number value when authoring a pipeline
  * [logging commands](https://docs.microsoft.com/en-us/azure/devops/pipelines/scripts/logging-commands?view=azure-devops&tabs=bash) - logging commands are how tasks and scripts communicate with the agent
  * [pipelines trigger](https://docs.microsoft.com/en-us/azure/devops/pipelines/build/triggers?view=azure-devops) - use triggers to run a pipeline automatically
  * [predefined variables](https://docs.microsoft.com/en-us/azure/devops/pipelines/build/variables?view=azure-devops&tabs=yaml) - variables give you a convenient way to get key bits of data into various parts of your pipeline. this is a list of predefined variables that are available for your use.
  * [templates](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=azure-devops) - templates let you define reusable content, logic, and parameters
  * [variables](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/variables?view=azure-devops&tabs=yaml%2Cbatch) - variables give you a convenient way to get key bits of data into various parts of the pipeline
  * [yaml schema reference](https://docs.microsoft.com/en-us/azure/devops/pipelines/yaml-schema?view=azure-devops&tabs=schema%2Cparameter-schema) - detailed reference guide to azure pipelines yaml pipelines
* [automatic app versioning](https://www.wagner-dev.com/azure-pipelines-automatic-app-versioning.html) - learn how you can use azure pipelines to automatically generate a semantic version number

## repos
* [overview](https://azure.microsoft.com/en-us/services/devops/repos/) - collaborate on code development using free Git public and private repositories, pull requests, and code review
* [documentation](https://docs.microsoft.com/en-us/azure/devops/repos/index?view=azdevops) - azure repos documentation

## test plans
* [overview](https://azure.microsoft.com/en-us/services/devops/test-plans/) - improve your overall code quality by using manual and exploratory testing services for your apps
* [documentation](https://docs.microsoft.com/en-us/azure/devops/test/index-tp?view=azdevops) - azure test plans documentation

## artifacts
* [overview](https://azure.microsoft.com/en-us/services/devops/artifacts/) - create, host, and share packages with your team
* [documentation](https://docs.microsoft.com/en-us/azure/devops/artifacts/index?view=azdevops) - azure artifacts documentation

## extensions
* [aws toolkit for azure devops](https://marketplace.visualstudio.com/items?itemname=amazonwebservices.aws-vsts-tools) - the aws toolkit for azure devops adds tasks to easily enable build and release pipelines in azure devops to work with aws services
* [azure pipelines for vs code](https://marketplace.visualstudio.com/items?itemName=ms-azure-devops.azure-pipelines) - this extentions adds syntax highlighting and autocompletion for azure pipelines yaml to vs code. it also helps you set up continuous build and deployment for azure webapps without leaving vs code
* [delivery plans](https://marketplace.visualstudio.com/items?itemname=ms.vss-plans) - delivery plans allow us to create a timelined overview over all iterations and planned work items cross projects and teams
* [feature timeline and epic roadmap](https://marketplace.visualstudio.com/items?itemname=ms-devlabs.workitem-feature-timeline-extension) - this extention can be used to plan epics (cross projects) and features in a project over all iterations. also it shows the status and progress of work items to feature completion
* [gittools](https://marketplace.visualstudio.com/items?itemName=gittools.gittools) -  looks at your git history and works out the semantic version of the commit being built. it works with most branching strategies 
* [market place](https://marketplace.visualstudio.com/azuredevops) - extensions for azure devops
* [retrospective board](https://marketplace.visualstudio.com/items?itemname=ms-devlabs.team-retrospectives) - easy way to create customizable retrospective boards. it allows us to quickly set up for sprint iterations and has all the abilities like vote, group, collect and categorize team input
* [team calendar](https://marketplace.visualstudio.com/items?itemname=ms-devlabs.team-calendar) - the team calendar allows teams to organize while not having to sync company calendars

## widget
* [team project health on dashboard](https://marketplace.visualstudio.com/items?itemname=ms-devlabs.teamprojecthealth) - this widget provides a brief overview of project health for instance pipeline runs and more details
* [work item details on dashboard](https://marketplace.visualstudio.com/items?itemname=ms-devlabs.workitemdetails) - the work item details can be displayed on the dashboard to give for example stakeholders a brief and quick overview of that is currently in progress

## others
* [azure demo generator](https://azuredevopsdemogenerator.azurewebsites.net/) - helps you create projects on your azure devops organization with pre-populated sample content that includes source code, work items, iterations, service endpoints, build and release definitions based on a template you choose
* [azure devops blog](https://devblogs.microsoft.com/devops/) - devops, git, and agile updates from the team building azure devops
* [azure devops documentation](https://github.com/MicrosoftDocs/azure-devops-docs) -  home of the official azure devops documentation
* [azure devops features timeline](https://docs.microsoft.com/en-us/azure/devops/release-notes/) - release notes and features timeline from azure devops team
* [azure devops lab](https://azuredevopslabs.com/) - exercises and examples of use of azure devops services
* [azure periodic table](http://www.concurrency.com/landing/azure-periodic-table) - periodic table for all services provided by azure
* [microsoft learn](https://docs.microsoft.com/en-us/learn/) - microsoft learning platform with different learning paths available
  * [learning path for azure devops](https://docs.microsoft.com/en-gb/learn/paths/evolve-your-devops-practices/)
