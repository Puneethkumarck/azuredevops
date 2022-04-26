# What is Azure DevOps?

Azure DevOps is a Software as a service (SaaS) platform from Microsoft that provides an end-to-end DevOps toolchain for developing and deploying software.

It also integrates with the most-leading tools on the market and is an excellent option for orchestrating a DevOps toolchain.

## What does Azure DevOps provide?

Azure DevOps includes a range of services covering the complete development life cycle.

* Azure Boards: agile planning, work item tracking, visualization, and reporting tool.
* Azure Pipelines: a language, platform, and cloud-agnostic CI/CD platform-supporting containers or Kubernetes.
* Azure Repos: provides cloud-hosted private git repos.
* Azure Artifacts: provides integrated package management with support for Maven, npm, Python, and NuGet package feeds from public or private sources.
* Azure Test Plans: provides an integrated planned and exploratory testing solution.
Also, you can use Azure DevOps to orchestrate third-party tools.
  
## What is GitHub?

GitHub is a Software as a service (SaaS) platform from Microsoft that provides Git-based repositories and DevOps tooling for developing and deploying software.

It has a wide range of integrations with other leading tools.

### What does GitHub provide?

GitHub provides a range of services for software development and deployment.

* <b>Codespaces:</b> Provides a cloud-hosted development environment (based on Visual Studio Code) that can be operated from within a browser or external tools. Eases cross-platform development.
* <b>Repos:</b> Public and private repositories based upon industry-standard Git commands.
* <b>Actions:</b> Allows for the creation of automation workflows. These workflows can include environment variables and customized scripts.
* <b>Packages:</b> The majority of the world's open-source projects are already contained in GitHub repositories. GitHub makes it easy to integrate with this code and with other third-party offerings.
* <b>Security:</b> Provides detailed code scanning and review features, including automated code review assignment.

## Explore an authorization and access strategy

Azure DevOps Services uses enterprise-grade authentication. To protect and secure your data, you can use:

* Microsoft account.
* GitHub account.
* Azure Active Directory (Azure AD).

Tools like Visual Studio and Azure DevOps natively support the use of Microsoft Accounts and Azure AD. Eclipse can also support this form of authentication if you install a Team Explorer Everywhere plug-in.

## Personal access tokens

Use personal access tokens (PAT) for tools that do not directly support Microsoft accounts or Azure AD for authentication. Also, if you want them to integrate with Azure DevOps.

For example, tools like:

* Git-based repositories.
* NuGet.
* Xcode.

These tokens can be set up using Git Credential managers, or you can create them manually.

Personal access tokens are also helpful when establishing access to command-line tools, external tools, and tasks in build pipelines.

Also, when calling REST-based APIs, you do not have a UI popping out to do the authentication. When access is no longer required, you can then revoke the personal access token.

## Security groups

Azure DevOps is pre-configured with default security groups. Default permissions are assigned to the default security groups. But you can also configure access at the organization level, the collection level, and the project or object level.

In the organization settings in Azure DevOps, you can configure app access policies. Based on your security policies, you might allow alternate authentication methods, enable third-party applications to access via OAuth, or even allow anonymous access to some projects.

For even tighter control, you can set conditional access to Azure DevOps. It offers simple ways to help secure resources when using Azure Active Directory for authentication.

## Multifactor authentication

Conditional access policies such as multifactor authentication can help to minimize the risk of compromised credentials.

As part of a conditional access policy, you might require:

* Security group membership.
* A location or network identity.
* A specific operating system.
* A managed device, or other criteria.

## Migrate or integrate existing work management tools

Both Azure DevOps and GitHub can be integrated with different kinds of work management tools.

As an example, in the Visual Studio Marketplace, Microsoft offers Trello integration tooling.

Migrating from other work management tools to Azure DevOps takes considerable planning.

Most work management tools are highly configurable by the end user. There might not be a tool available that will do the migration without further configuration.


## Jira

Jira is a commonly used work management tool.

In the Visual Studio Marketplace, Solidify offers a tool for Jira to Azure DevOps migration. It migrates in two phases. Jira issues are exported to files, and then the files are imported to Azure DevOps.

If you decide to write the migration code yourself, the following blog post provides a sample code that might help you get started: [Migrate your project from Jira to Azure DevOps.](http://www.azurefieldnotes.com/2018/10/01/migrate-your-project-from-jira-to-azure-devops/)

## Migrate or integrate existing test management tools

Azure Test Plans are used to track manual testing for sprints and milestones, allowing you to follow when that testing is complete.

Azure DevOps also has a Test Feedback extension available in the Visual Studio Marketplace. The extension is used to help teams do exploratory testing and provide feedback.

All team members and other stakeholders can use the extension to submit bugs or provide feedback. For example:

* Developers.
* Product owners.
* Managers.
* UX.
* UI engineers.
* Marketing teams.
* Early adopters.

[Apache JMeter](https://docs.microsoft.com/en-us/azure/devops/test/load-test/get-started-jmeter-test) is open-source software written in Java and designed to load test and measure performance.

Pester is a tool that can be used to automate the testing of PowerShell code.

SoapUI is another testing framework for SOAP and REST testing.

If you are using Microsoft Test Manager, you should plan to migrate to Azure Test Plans instead.

For more information, search for Test Management at Visual Studio Marketplace.



# Introduction to Azure Repos

Azure Repos is a set of version control tools that you can use to manage your code.

Whether your software project is large or small, using version control is a good idea.

Azure Repos provides two types of version control:

* Git: distributed version control
* Team Foundation Version Control (TFVC): centralized version control


## What do I get with Azure Repos?

* Use of free private Git repositories, pull requests, and code search: Get unlimited private Git repository hosting and support for TFVC that scales from a hobby project to the world’s largest repository.
* Support for any Git client: Securely connect with and push code into your Git repos from any IDE, editor, or Git client.
* Web hooks and API integration: Add validations and extensions from the marketplace or build your own-using web hooks and REST APIs.
* Semantic code search: Quickly find what you are looking for with a code-aware search that understands classes and variables.
* Collab to build better code: Do more effective Git code reviews with threaded discussion and continuous integration for each change. Use forks to promote collaboration with inner source workflows.
* Automation with built-in CI/CD: Set up continuous integration/continuous delivery (CI/CD) to trigger builds, tests, and deployments automatically. It with every completed pull request-using Azure Pipelines or your tools.
* Protection of your code quality with branch policies: Keep code quality high by requiring code reviewer sign-out, successful builds, and passing tests before merge pull requests. Customize your branch policies to maintain your team’s high standards.
* Usage of your favorite tools: Use Git and TFVC repositories on Azure Repos with your favorite editor and IDE.


## Introduction to GitHub

GitHub is the largest open-source community in the world. Microsoft owns GitHub. GitHub is a development platform inspired by the way you work.

You can host and review code, manage projects, and build software alongside 40 million developers from open source to business.

GitHub is a Git repository hosting service, but it adds many of its features.

While Git is a command-line tool, GitHub provides a Web-based graphical interface.

It also provides access control and several collaboration features, such as wikis and essential task management tools for every project.

So what are the main benefits of using GitHub? Nearly every open-source project uses GitHub to manage its project.

Using GitHub is free if your project is open source and includes a wiki and issue tracker that makes it easy to have more in-depth documentation and get feedback about your project.


## Link GitHub to Azure Boards

Azure Boards has direct integration with Azure Repos, but it can also be integrated with GitHub.

Integrating GitHub with Azure Boards lets you plan and track your work by linking GitHub commits, pull requests, and issues, directly to work items in Boards.

## Azure Boards App

The integration is created by using the Azure Boards App. Acting as a bridge between Azure Boards and GitHub.

To install the app, you must be an administrator or owner of the GitHub repository or the GitHub organization.

The app is installed from the GitHub Marketplace. Azure Boards App


## Authenticating to GitHub

Azure Boards can connect to GitHub. For GitHub in the cloud, when adding a GitHub connection, the authentication options are:

Username/Password
Personal Access Token (PAT)
For a walkthrough on making the connection, see: [Connect Azure Boards to GitHub.](https://docs.microsoft.com/en-us/azure/devops/boards/github/connect-to-github)

