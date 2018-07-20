This repo demonstrates an issue with Cypress where the support files are not compiled by TypeScript.

This is happening on Windows 10 with Node 8.11.3 and Yarn as a package manager.

I added a custom command and declared it in the Cypress namespace, TypeScript is happy with it and I get no error in Visual Studio Code. However at runtime I get an error saying my custom command is not defined.

You can run `yarn cypress open` to see the issue.
