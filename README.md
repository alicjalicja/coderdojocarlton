## Requirements
NPM
Install the Node Package Manager https://nodejs.org/en/

##Install s3-upload module
https://npm.runkit.com/s3-upload-static
  npm install -g s3-upload

## Basic configuration
1. Create aws-credentials.json file with following info (make sure this file is excluded in .gitignore):
{
    "accessKeyId": "YOURACCESSKEY",
    "secretAccessKey": "YOURSECRETACCESSKEY",
    "region": "ap-southeast-2"
}
2. If you changed the project's file structure, update the aws-upload.conf.js file to include these changes

## Uploading files
  s3-upload
