# dotenv-samplefile-autosync

If you're tired of manually updating your .env.sample files to keep them in sync with their corresponding .env files, this package can help.

Install it as a dev-dependency in your project. The postinstall script will install a pre-push git hook that will update your .env.sample files to match their equivalent .env files in your project.

_You_ might forget to update your .env.sample files during local development, but your teammates will never know :)

---

## Notes

- Supports suffixed .env files (.env.staging, .env.production, etc.)
- This package is best installed as a **dev-dependency**
- This package does not currently support Windows
- [WARNING] If you have an existing pre-push hook installed, this package will overwrite it
