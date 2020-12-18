_Create a project and init NPM_
1- mkdir <new folder>
2- npm init -y

_To create a package on NPM you need to start Git_
1- git init
2- git add .
3- git commit -m "initial commit"

_Then this NPM commands_
1- npm login
2- npm publish --access public

_To versioning package in package.json_
npm version patch (or change manually on package.json)

npm publish (to publish whenever we run a new build)

_To unpublish_
npm unpublish <@oganization/package_name> -f

_To update a package on another service_
npm update <@oganization/package_name>
