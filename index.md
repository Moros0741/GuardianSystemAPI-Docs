## Guardian System API Documentation

The Guardian System was created with the intentions of allowing Moderation bots on discord to have access to one database to fetch information about bad actors on the platform. With the Guardian System API you will be able to interact with and submit data to the database right from within your code. However, with this in mind, before we dive in there are some ground rules to set. 

### Ground Rules

Our endpoints allow you to submit data using POST requests made to the `api/v1/reports` endpoint. Under no circumstances should reporting be a public feature/command for your application. 

This is to limit the amount of incoming requests and avoid any requests that may not fit the overall criteria of the database. 

We encourage you as a developer to write a system into your application for automated POST requests for submitting reports based on a auto-moderation feature, since automods are set with specific criteria that may align with our criteria better.

Your application must always ahere to the Discord Developer Terms of Service and Policies. If you or your application are found to be in violation of said terms and policies, it will result in an immediate revocal of your API TOKEN and blacklist from the API. 

As developers it is our job to lay a solid foundation of trust and integrity for the communities we support with our programs, applications found to be malicious intentionally or otherwise will be removed from the API without repeal. 

### What Type of API is Guardian System?

As you could probably gather from the above information, The Guardian System is a REST API. A REST API, allows programs of anykind to access data on the servers via HTTP requests made over the internet. Think of when you open Discord's browser, Your browser is sending an HTTP GET request to the Discord Routers for the proper pages to display. This is essentially the same concept but without webpages to display. All Content-Types are `application/json`. Out of the many types to choose from we chose this type because it adheres to a common data transfer language interpretable by most every Discord application out there.

### How Do I Get My Access Token?

ACCESS TOKENS are given out after a short screening process to verify the legitimacy of your application. To prevent bad actors from using the bot to receive and manipulate information, we require all applications to be Discord Verified applications. Once you have provided the neccessary information to validate your application an ACCESS TOKEN will be sent to you. To start the verification process with use you can join our support server here: [Guardian System Support](https://discord.gg/eVUgfYEUaw)

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Moros0741/GuardianSystemAPI-Docs/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
