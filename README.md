# Appwrite

WIP deployment for Appwrite behind [POCADEC](https://github.com/digitoolmedia/dm-docker-pocadec)

### Notes

- Function domains (both custom and auto-generated) arent' working atm.
- Due to an Appwrite limitation the `_APP_VCS_GITHUB_PRIVATE_KEY` env variable isn't working correctly and require manual definition and exposure within the compose file.
