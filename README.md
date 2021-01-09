# My Codespace

[Twitter: @stvansolano](https://twitter.com/stvansolano)

## Do you like it? Give a Star! :star:

If you like or are using this project to learn or start your own solution, please give it a star. I appreciate it!

A ready-to-use, templated GitHub Codespace that I regularly use for VS Code on GitHub (Codespaces).

## Batteries included

- Docker
- NodeJS
- .NET (if needed)

## Bot Framework links:

- https://github.com/microsoft/BotBuilder-Samples.git

## To be installed locally
- NPM ^v15 (no codespace)
- Bot emulator: https://github.com/microsoft/BotFramework-Emulator/releases

## NGROK & External Bots
- https://github.com/Microsoft/BotFramework-Emulator/wiki/Getting-Started#connect-to-a-bot-hosted-remotely
- https://ngrok.com/download

# How to run it (Codespace)

1) Clone the [samples](https://github.com/microsoft/BotBuilder-Samples.git) - https://github.com/microsoft/BotBuilder-Samples.git
2) Install `ngrok`
3) Copy forwarded/tunneled ngrok URL - `curl https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip --output ngrok.zip && unzip ngrok && ./ngrok http 3978`
4) Pick a sample (`cd` to folder), then `npm install` and start - `npm run build && npm start` 
5) Make a New Bot file (External.bot) and use `[URL-goes-here]/api/messages` endpoint
6) Open bot in Emulator

## Build, test & deploy your bots
- Build your bot. .NET | [JavaScript](https://docs.microsoft.com/en-us/azure/bot-service/javascript/bot-builder-javascript-quickstart?view=azure-bot-service-4.0) | Python and others
- Using Continuous Integration.

## Using Yeoman (JavaScript)

```
npm install -g yo
npm install -g generator-botbuilder
```

> Codespace issue with Yeoman: chmod g+rwx /root /root/.config /root/.config/configstore

## Connect & Monitor your bots
- Channels - https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0

# Bot Framework concepts

- Connector

- Channel

- Activity

    - Types: Message, Ping, Typing, Conversation Update, Contact Relation Update, Delete User Data

- Message
    - Replies
    - Markdown for responses

- Dialogs (prompts)
    - Primary way to send information

- State

## Bot Composer

Links:
- https://github.com/microsoft/BotFramework-Composer
- https://docs.microsoft.com/en-us/composer/introduction
- https://docs.microsoft.com/en-us/composer/quickstart-create-bot
- https://docs.microsoft.com/en-us/composer/how-to-define-intent-entity
- https://docs.microsoft.com/en-us/azure/bot-service/file-format/bot-builder-lu-file-format?view=azure-bot-service-4.0

## Azure Bot Service
Links:
- Azure Bot Service: https://docs.microsoft.com/en-us/azure/bot-service/javascript/bot-builder-javascript-quickstart?view=azure-bot-service-4.0

- Channels

- Bots for Teams: https://docs.microsoft.com/en-us/microsoftteams/platform/bots/how-to/create-a-bot-for-teams

- Bots for Telgram: - https://docs.microsoft.com/en-us/previous-versions/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-3.0

And others.

## Recent updates and new stuff
- https://techcommunity.microsoft.com/t5/azure-ai/ignite-2020-conversational-ai-updates/ba-p/1691841
- https://techcommunity.microsoft.com/t5/azure-ai/build-2020-introducing-bot-framework-virtual-assistant-1-0/ba-p/1407833