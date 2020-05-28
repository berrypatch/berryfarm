# The Berry Farm

This is the main repository of applications for use with
[Berrypatch](https://github.com/berrypatch/berrypatch). For more information,
see that repo.

## Adding a new App

To add a new app:

1. Create a new skeletal app using `bp dev mkapp`. Be sure the app name is unique.
2. Modify the `docker-compose.tmpl.yml`, and add any configuration variables your app needs to the `berry.json` file.
3. Open a pull request here.
