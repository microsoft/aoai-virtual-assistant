# AOAI Virtual Assistant Accelerator

Quickly get started with virtual assistants using Azure OpenAI

## Setup

- Set up an Azure OpenAI resource. You may need to request access if your subscription is not enabled yet
![Configure AOAI Service](./readme_images/configure-aoai.png)
- Create a GPT 3.5 or GPT 4 deployment
![Configure AOAI Deployment](./readme_images/configure-deployment.png)
- Clone the repository:

    `git clone https://github.com/microsoft/aoai-virtual-assistant.git`

- Create the app settings file at `./GPTVirtualAssistant/settings/appsettings.json`. Use the example file provided as a template. You will need to fill in the information in the "openai" field.
![Configure AOAI Credentials](./readme_images/configure-settings.png)
- Open the project in Bot Framework Composer
![Configure AOAI Credentials](./readme_images/open-botcomposer.png)
- [Publish your bot](https://learn.microsoft.com/en-us/composer/how-to-publish-bot?tabs=v2x)
![Publish bot](./readme_images/publish-bot.png)
- [Configure end-user channels](https://learn.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0)
![Configure end-user channels](./readme_images/configure-channels.png)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
