# Copilot Static Web Demo

This is a base demo applcation that can be used for demonstrations of basic with copilot functionality or for examples in other trainings of the GitHub Copilot Adoption Program.

## About the app:
This is a basic website containing just a few static webpages and a server created with NodeJS by using ExpressJS Framework.

## How to create the app.
This app can be created by using the following prompt on GitHub Copilot.

```
@workspace /new I want you to build the structure of a new web project for a static website. The site consists of three main pages: Index, About, and Contact Us. The website is intended to display information about the solar system and is named "app". Therefore, you should include information about the planets that make up the solar system: Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune. In some parts, Pluto is recognized as a planet. Therefore, include information about Pluto as well. And don't forget to include the Sun and all its relevant information. This will go on the index page. On the about us page, state that we are a small group of astronomy enthusiasts with a mission to educate and share information about the planets. (In this part, as an AI model, you should generate rich and useful content). Finally, on the Contact Us page, create a contact form that collects the following information: First Name, Last Name, Email, Country, and a large text field for users to write their anecdotes.

This website should be developed using HTML5, CSS3, JavaScript, and the latest version of Bootstrap as the style and component library. To provision this website, you should use NodeJS with the ExpressJS framework to provision and make this static website available. The entire structure of this application should be created within a folder called "app" located in the root directory of this repository. It is very important not to repeat the web pages, i.e., do not generate the same page twice, and above all, do not forget to generate the .gitignore file for this project.
```

**Troubleshooting: .gitignore**  
If the `.gitignore` file is not generated during the use of the command, simply create a new `.gitignore` file inside the `app` folder and use the key combination `ctrl`+`i` on Windows or `cmd`+`i` on MacOS to open the Copilot "in-line" chat. Write the following prompt for Copilot to generate a basic .gitignore structure for you.

If you want to see the final version of this website, checkout to the `solved` branch to see final results.
```sh
git checkout solved
```