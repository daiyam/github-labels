## Install

```sh
npm -g install github-label-manager
```

## Settings 

The command will need your GitHub username and a token provided by GitHub

### Generate a new token

Go to [this page](https://github.com/settings/tokens) and create a new token with the **repo** and **public_repo** permissions enabled.

### Authentication via environment variable
 
Add the following environment variables in your bash profile file:

```
export GITHUB_USER = "user"
export GITHUB_TOKEN = "token"
```

## Usage

### Remove existing labels

```sh
glm clear owner:repo
```

### Add your own labels

```sh
glm import owner:repo all.json
```