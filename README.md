Install Astro with the Automatic CLI
Ready to install Astro? Follow this guide to using the create astro CLI to get started.
 PREFER TO INSTALL ASTRO MANUALLY?

Read our step-by-step manual installation guide instead.
Prerequisites
Section titled Prerequisites
Node.js - v18.14.1 or higher.
Text editor - We recommend VS Code with our Official Astro extension.
Terminal - Astro is accessed through its command-line interface (CLI).
Installation
Section titled Installation
create astro is the fastest way to start a new Astro project from scratch. It will walk you through every step of setting up your new Astro project. It allows you to choose from a few different official starter templates or you can use any existing project on GitHub with the --template argument.
 ONLINE PREVIEWS

Prefer to try Astro in your browser? Visit astro.new to browse our starter templates and spin up a new Astro project without ever leaving your browser.
1. Run the Setup Wizard
Section titled 1. Run the Setup Wizard
Run the following command in your terminal to start our handy install wizard:
npm
pnpm
Yarn
Terminal window
# create a new project with npm
npm create astro@latest

You can run create astro anywhere on your machine, so there’s no need to create a new empty directory for your project before you begin. If you don’t have an empty directory yet for your new project, the wizard will help create one for you automatically.
If all goes well, you should see a “Liftoff confirmed. Explore your project!” message followed by some recommended next steps. cd into your new project directory to begin using Astro.
If you skipped the npm install step during the CLI wizard, then be sure to install your dependencies before continuing.
2. Start Astro ✨
Section titled 2. Start Astro ✨
Astro comes with a built-in development server that has everything you need for project development. The astro dev command will start the local development server so that you can see your new website in action for the very first time.
Every starter template comes with a pre-configured script that will run astro dev for you. Use your favorite package manager to run this command and start the Astro development server.
npm
pnpm
Yarn
Terminal window
npm run dev

If all goes well, Astro should now be serving your project on http://localhost:4321/!
Astro will listen for live file changes in your src/ directory, so you will not need to restart the server as you make changes during development.
If you aren’t able to open your project in the browser, go back to the terminal where you ran the dev command and look to see if an error occurred, or if your project is being served at a different URL than the one linked to above.
Starter Templates
Section titled Starter Templates
You can also start a new astro project based on an official example or the main branch of any GitHub repository by passing a --template argument to the create astro command.
npm
pnpm
Yarn
Terminal window
# create a new project with an official example
npm create astro@latest -- --template <example-name>

# create a new project based on a GitHub repository’s main branch
npm create astro@latest -- --template <github-username>/<github-repo>

By default, this command will use the template repository’s main branch. To use a different branch name, pass it as part of the --template argument: <github-username>/<github-repo>#<branch>.
Explore our themes and starters showcase where you can browse themes for blogs, portfolios, documentation, landing pages, and more! Or, search on GitHub for even more starter projects.
Next Steps
Section titled Next Steps
Success! You are now ready to start building with Astro! 🥳
Here are a few topics that we recommend exploring next. You can read them in any order. You can even leave our documentation for a bit and go play in your new Astro project codebase, coming back here whenever you run into trouble or have a question.
📚 Add a framework: Learn how to extend Astro with support for React, Svelte, Tailwind and more using npx astro add in our Integrations guide.
📚 Deploy your site: Learn how to build and deploy an Astro project to the web in our Deployment guide.
📚 Understand your codebase: Learn more about Astro’s project structure in our Project Structure guide.