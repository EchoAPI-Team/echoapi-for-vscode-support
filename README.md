# EchoAPI for VS Code

![EchoAPI for VS Code.png](https://assets.echoapi.com/upload/user/216769532487155712/log/935d7e4c-f019-4ca1-a723-18dbc3299bf2.png "EchoAPI for VS Code.png")

EchoAPI for VS Code is a lightweight REST API client extension for Visual Studio Code, designed with a focus on simplicity, clean design, and local storage, and it's **free** to use.

## Why EchoAPI?

EchoAPI has a few standout features:
1. **No login required**: Just install and start using it.
2. **Supports Scratch Pad**: Makes jotting down quick notes and ideas super easy.
3. **Ultra-lightweight**: It’s incredibly fast and doesn’t bloat your system.
4. **100% compatible with Postman script syntax**: You can switch over without having to relearn anything.

## Installing EchoAPI for VS Code

![Installing EchoAPI for VS Code.png](https://assets.echoapi.com/upload/user/216769532487155712/log/41df1737-986e-4edf-bdf8-00b564cf9468.png "Installing EchoAPI for VS Code.png")

Getting started with EchoAPI is a breeze. Just navigate to the VS Code Extensions Marketplace, search for EchoAPI, and hit install. No additional tools or sign-ins are necessary—everything operates straight from your VS Code sidebar.

## Creating New Requests

![Creating New Requests.png](https://assets.echoapi.com/upload/user/216769532487155712/log/5a89a186-4ba5-44fd-9bf3-7bbdfca30048.png "Creating New Requests.png")

To create a new request, start by opening the EchoAPI tab where you’ll see options for recent activities, collections, and environments. It’s pretty intuitive if you’ve used Postman before. Right-click on the collection list to create a New Collection, name it, and then right-click on the collection name to add a new request.

## Variables and Environments


![EchoAPI is 100% compatible with Postman script syntax.png](https://assets.echoapi.com/upload/user/216769532487155712/log/a067abc0-29b0-4e4d-bd17-a0172acf4eb8.png "EchoAPI is 100% compatible with Postman script syntax.png")

Just like in Postman, you can use variables and manage environments in EchoAPI. **EchoAPI is 100% compatible with Postman script syntax.** To activate a specific environment for your tests, just set it as active (indicated by a star next to the environment name). Importing and exporting environments is compatible with Postman 2.1.0 format and .env files.

## System Variables

![System Variables.png](https://assets.echoapi.com/upload/user/216769532487155712/log/d8260473-64cc-4f33-b057-7751f4ed8333.png "System Variables.png")

EchoAPI also has a set of system variables that streamline generating unique data. Prepend $ before the variable name to use them:
- `{{$guid}}` - random UUID number
- `{{$email}}` - random email string

## Script-less Testing


![Testing in EchoAPI is straightforward and script-less.png](https://assets.echoapi.com/upload/user/216769532487155712/log/415543b9-535d-42aa-826d-7f23e995ea57.png "Testing in EchoAPI is straightforward and script-less.png")


Testing in EchoAPI is straightforward and script-less. Choose a parameter from the dropdown menu, set your condition and value, and you’re done! There are plenty of parameters and conditions to choose from, like ResponseCode, ResponseBody, or Content-Type. You can even set values from API responses to environment variables or verify specific JSON path values.

## Authentication

![EchoAPI supports various authorization types.png](https://assets.echoapi.com/upload/user/216769532487155712/log/4040d8c6-05ae-4cba-b1f9-54b0e14fd81c.png "EchoAPI supports various authorization types.png")

EchoAPI supports various authorization types, including None, Inherit, Basic Auth, Bearer, and OAuth 1.0. This is super useful for testing secured APIs that require credentials or tokens.

## Useful Links

EchoAPI is continually growing, and I’ll definitely keep an eye on its progress. Here are some useful links:
- [Website](https://www.echoapi.com/)
- [Documentation](https://www.echoapi.com/wiki/docs/vscode/start)
- [Twitter](https://x.com/EchoApiTeam)
- [Youtube](https://www.youtube.com/@EchoAPI-Team)

Give EchoAPI a try and see how it compares to Postman for your API testing needs!
