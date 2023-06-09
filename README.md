# ausiliario

`ausiliario` is a Go package for running a local private registry using
verdaccio and automating package publishing.

## Installation

You can install ausiliario using the following npm command:

```shell
npm install ausiliario
```

## Usage

#### 1. Create a config file

Create a config.yml file in your project directory and fill in the configuration
information in the following format: makefile

```
verdaccio_url: your-registry-url
username: your-username 
password:your-password 
email: your-email
```

#### 2. Use the ausiliario program for login and publish

Add the publish script to your package.json:

```
"scripts": {
  "publish": "ausiliario"
}
```

Run the script:

```shell
npm run publish
```
