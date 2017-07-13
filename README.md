# Cloud Desc Co. - Toolchain

This toolchain deploys the [Project Desc](https://github.com/Conciergedevelopers/project-desc) project.

Get started with this project, which is an online desc application that consists of microservices:

* [desc-catalog][catalog_github_url] - An API to retrieve and update a catalog of desc records
* [desc-orders][orders_github_url] - An API to retrieve and update a list of desc record orders made by customers
* [desc-bot][bot_github_url] - UI that provides a chat bot interface for users to query their health benefits and file claims.
* [desc-bot-dashboard][dashboard_github_url] - A user interface showing an history of the bot chats for further analysis.
* [desc-bot-ios][ios_github_url] - An iOS application for the chat bot.
* [desc-bot-android][android_github_url] - An Android application for the chat bot.

## Create the toolchain

1. Ensure you have 2GB of free memory and space for 5 additional services in your organization.

1. It is recommended to create a new space in your organization. This helps grouping the apps and services together in the console.

1. **To get started, click this button:**

  [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://bluemix.net/deploy?repository=https://github.com/conciergedevelopers/desc-toolchain-master.git)

  Clicking it will:
  * **create 4 GitHub repositories** with the required source code for all the application components;
  * **instantiate the toolchain** in your Bluemix org and space;
  * **trigger the toolchain**, thereby deploying the selected branches (default to master) for all application components.


The toolchain is preconfigured for:

- issue tracking
- source control
- continuous delivery and integration (CI/CD)
- unit and code coverage testing
- blue-green deployment

---

### Learn more

* Bluemix DevOps Services: https://new-console.ng.bluemix.net/devops
* Documentation on [Bluemix Toolchains][toolchains_overview_url]
* InterConnect 2016 [video recording][toolchains_interconnect_video_url]
* [IBM Bluemix Garage Method][garage_method_url]

<!--Links-->
[bot_github_url]: https://github.com/Conciergedevelopers/desc-bot
[orders_github_url]: https://github.com/Conciergedevelopers/desc-orders
[catalog_github_url]: https://github.com/Conciergedevelopers/desc-catalog
[dashboard_github_url]: https://github.com/Conciergedevelopers/desc-bot-dashboard
[ios_github_url]: https://github.com/Conciergedevelopers/desc-bot-ios
[android_github_url]: https://github.com/Conciergedevelopers/desc-bot-android
[toolchains_overview_url]: https://new-console.ng.bluemix.net/docs/toolchains/toolchains_overview.html
[garage_method_url]: https://www.ibm.com/devops/method


