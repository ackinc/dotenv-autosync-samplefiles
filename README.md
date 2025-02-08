If you're tired of manually updating your .env.sample files to keep them in sync with their corresponding .env files, this package can help.

Install it as a dev-dependency in your project. The project must be using git for version control.

The postinstall script will install a pre-push git hook that will update your .env.sample files with missing keys from the .env files in your project
