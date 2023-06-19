# config-file-heroku-buildpack

Heroku Buildpack to create a file based on a base64 encoded ENV in a heroku app.

Steps to use this Buildpack:

- Add the following config vars in heroku app settings:
  - `TARGET_FILE_NAME` containing the target name
  - `TARGET_FILE_BASE64` containing the base64 encoded data to output to the `TARGET_FILE_NAME` file.
