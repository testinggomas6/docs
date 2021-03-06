# Getting started with Codacy

Codacy automatically identifies issues through static code review analysis and notifies you on security issues, code coverage, code duplication, and code complexity in every commit and pull request.

To get started, head to [<span class="skip-vale">codacy.com</span>](https://www.codacy.com/) and click **Get started**.

## 1. Sign up {: id="sign-up"}

Signing up with a Git provider such as GitHub, GitLab, or Bitbucket links your Codacy user with your Git provider user, making it easier to add repositories to Codacy and invite your teammates.

Codacy will ask you to have access to your Git provider during the authorization flow. [Check the permissions that Codacy requires and why](which-permissions-does-codacy-need-from-my-account.md).

## 2. Account details {: id="account-details"}

You'll be asked to fill in a few details about your company so we know a bit more about your use case.

## 3. Choose an organization {: id="choose-organization"}

Now, you'll need to join one or more organizations that contain your repositories. The organization with the same name as your Git provider username contains your personal repositories. The selected organizations will then be synced with Codacy so that managing your team permissions is easy. Read more about [what synced organizations do](../organizations/what-are-synced-organizations.md). 

!!! tip
    If you can't see the organization you are looking for, [follow these troubleshooting instructions](../faq/general/why-cant-i-see-my-organization.md).

![Choosing an organization](images/getting-started-choose-organization.png)

To start adding your repositories, select one of the organizations and click **Go to add repositories**.

## 4. Add repositories {: id="add-repositories"}

As a final step, add the repositories that you wish to analyze. Codacy will start the first analysis and set up everything required to ensure your next commits on those repositories are analyzed.

![Adding repositories](images/getting-started-add-repository.png)

## You're all set! 🎉 {: id="all-set"}

Codacy begins an initial analysis as soon as you add a repository, and displays an overview of the code quality of your repository when the analysis is complete.

After that, you can continue to explore and configure Codacy for your repository:

-   [Check the static analysis results](../repositories/issues-view.md) on the Issues page
-   [Configure the code patterns](../repositories-configure/code-patterns.md) that Codacy uses to analyze your repository
-   [Ignore files](../repositories-configure/ignore-files-from-codacy-analysis.md) that you want to exclude from the Codacy analysis
-   [Configure your quality settings](../repositories/quality-settings.md) for pull requests
-   [Add coverage reports to Codacy](../coverage-reporter/adding-coverage-to-your-repository.md)
-   [Add a Codacy badge to your repository](../repositories/badges.md) displaying the current code quality grade or code coverage

![Repository dashboard](../repositories/images/repository-dashboard.png)
