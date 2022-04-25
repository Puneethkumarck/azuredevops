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

