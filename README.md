# npm tutorial

<ol>
  <li><a href="#introduction">Introduction</a></li>
  <li><a href="#getting-npm">Getting npm</a></li>
  <li><a href="#npm-help">npm Help</a></li>
  <li><a href="#packagejson-file">package.json File</a></li>
  <li><a href="#package-json-defaults">package-lock.json File</a></li>
  <li><a href="#package-json-defaults">package json Defaults</a></li>
  <li><a href="#installing-local-packages">Installing Local Packages</a></li>
  <li><a href="#uninstalling-local-packages">Uninstalling Local Packages</a></li>
  <li><a href="#installing-global-packages">Installing Global Packages</a></li>
  <li><a href="#uninstalling-global-packages">Uninstalling Global Packages</a></li>
  <li><a href="#listing-packages">Listing Packages</a></li>
  <li><a href="#npm-versioning">npm versioning</a></li>
  <li><a href="#installing-from-package-json">Installing from package json</a></li>
  <li><a href="#updating-packages">Updating Packages</a></li>
  <li><a href="#npm-prune">npm Prune</a></li>
  <li><a href="#shortcuts">Shortcuts</a></li>
  <li><a href="#npm-scripts">npm Scripts</a></li>
</ol>

## Introduction
npm is a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js. It consists of a command line client, also called npm, and an online database of public and paid-for private packages, called the npm registry.

## Getting npm
Download the latest version of node JS as per OS
- <a href="https://nodejs.org/en/download">https://nodejs.org/en/download</a>
- **Version Check:** node -v

## npm Help
use
- **npm help** in command prompt
- **npm install -h** Diffrent way to install
- Help Search **npm help** -search update"
- **npm help** update (Open the documentation in browser)

## package.json File
- manage dependencies (Dev | Global | Local)
- Scripts for intial build and test
Using **npm init** you can create package.json file (After giving some answer), "npm init --yes" to create package.json with default answer

## package-lock.json File
**package-lock.json** is automatically generated for any operations where npm modifies either the node_modules tree, or package.json. It describes the exact tree that was generated, such that subsequent installs are able to generate identical trees, regardless of intermediate dependency updates.
- If you’re using npm ^5.x.x, by default a package-lock.json will be generated for you
- You should use package-lock to ensure a consistent install and compatible dependencies
- You SHOULD commit your package-lock to source control
- As of npm ^5.1.x, package.json is now able to trump package-lock.json, so you should experience much less of a headache
- No more deleting that package-lock just to run `npm install` and regenerate it
- Use semver if your app offers an API, and adhere to the rules of semver.

## package json Defaults
## Installing Local Packages
## Uninstalling Local Packages
## Installing Global Packages
## Uninstalling Global Packages
## Listing Packages
## npm versioning
## Installing from package json
## Updating Packages
## npm Prune
## Shortcuts
## npm Scripts
