# EchoAPI for VS Code

![EchoAPI for VS Code](https://github.com/user-attachments/assets/f72fabff-b726-4883-ab76-534bdd7db266)

EchoAPI for VS Code is a lightweight REST API client extension for Visual Studio Code, designed with a focus on simplicity, clean design, and local storage, and it's **free** to use.

## Why EchoAPI?

EchoAPI has a few standout features:
1. **No login required**: Just install and start using it.
2. **Supports Scratch Pad**: Makes jotting down quick notes and ideas super easy.
3. **Ultra-lightweight**: It’s incredibly fast and doesn’t bloat your system.
4. **100% compatible with Postman script syntax**: You can switch over without having to relearn anything.

## Installing EchoAPI for VS Code
![Installing EchoAPI for VS Code](https://www.echoapi.com/blog/content/images/2024/10/image-3.png)

Getting started with EchoAPI is a breeze. Just navigate to the VS Code Extensions Marketplace, search for EchoAPI, and hit install. No additional tools or sign-ins are necessary—everything operates straight from your VS Code sidebar.

## Creating New Requests

![Creating New Requests](https://github.com/user-attachments/assets/4d4422dc-ae7d-4e68-b90d-db784d30ef55)

To create a new request, start by opening the EchoAPI tab where you’ll see options for recent activities, collections, and environments. It’s pretty intuitive if you’ve used Postman before. Right-click on the collection list to create a New Collection, name it, and then right-click on the collection name to add a new request.

## Running a collection
Just pick the folder you want to run, right-click, and hit "Run All." That’s it!
![Running a collection](https://www.echoapi.com/blog/content/images/2024/10/image-4.png)

## Variables and Environments

![EchoAPI is 100% compatible with Postman script syntax](https://github.com/user-attachments/assets/ceb7762e-0c69-4f79-873c-1ac9bab71c38)

Just like in Postman, you can use variables and manage environments in EchoAPI. **EchoAPI is 100% compatible with Postman script syntax.** To activate a specific environment for your tests, just set it as active (indicated by a star next to the environment name). Importing and exporting environments is compatible with Postman 2.1.0 format and .env files.

## System Variables

![System Variables](https://github.com/user-attachments/assets/fefb6901-8704-475c-96ce-fafd15206b97)

EchoAPI also has a set of system variables that streamline generating unique data. Prepend $ before the variable name to use them:
- `{{$guid}}` - random UUID number
- `{{$email}}` - random email string

## Script-less Testing

![Testing in EchoAPI is straightforward and script-less](https://github.com/user-attachments/assets/a8eacc28-4566-40c5-8ecd-c580c11e8f27)

Testing in EchoAPI is straightforward and script-less. Choose a parameter from the dropdown menu, set your condition and value, and you’re done! There are plenty of parameters and conditions to choose from, like ResponseCode, ResponseBody, or Content-Type. You can even set values from API responses to environment variables or verify specific JSON path values.

## Authentication

![EchoAPI supports various authorization types](https://github.com/user-attachments/assets/0022873b-465c-46dc-a76c-e53cdb08de5d)

EchoAPI supports various authorization types, including None, Inherit, Basic Auth, Bearer, and OAuth 1.0. This is super useful for testing secured APIs that require credentials or tokens.

## Useful Links

EchoAPI is continually growing, and I’ll definitely keep an eye on its progress. Here are some useful links:
- [Website](https://www.echoapi.com/)
- [Documentation](https://www.echoapi.com/wiki/docs/vscode/start)
- [Twitter](https://x.com/EchoApiTeam)
- [Youtube](https://www.youtube.com/@EchoAPI-Team)

Give EchoAPI a try and see how it compares to Postman for your API testing needs!
