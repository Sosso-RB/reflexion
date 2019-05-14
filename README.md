# Reflexion

A sample web project with webpack-encore and http-server

## Installation

First, clone the repository
```
git clone https://github.com/Hugotgot/sample-project.git
```

Then, install dependencies
```
npm install
```

## Usage
There's two empty entry files provided in this project :
- **src/js/main.js**
- **src/scss/style.scss**

That's the files you should modify and write your code in.
You should, while working, run the command Encore Watch (see below) to compile assets.

The **index.html** is in the **public** folder and that's the one you should modify (import for the compiled js and css files are already in).

## Run
### Encore
#### Watch (dev)
```
npm run watch
```

#### Build 
```
npm run prod
```

### HTTP-Server
```
npm run serve
```

Now, your project is accessible at http://127.0.0.1:8088 !




## Collaborating
### Fork

- Fork the main repo (fork button top-right)
- Clone your repo on your computer

### Init

Add upstream branch

```
$ git remote add upstream https://github.com/GuillaumeLagouy/reflexion.git
```

### Working

- Create a branch for your new feature and work on it
```
$ git checkout -b feature#name-of-the-feature
$ git pull upstream develop
```

- Commit your changes and push your branch to your repo
```
$ git commit -m "..."
$ git push origin feature#name-of-the-feature
```

- Create a pull request to the upstream repo (github website)

- When the commits are merged, go back to develop branch and pull upstream

```
$ git checkout develop
$ git pull upstream develop
```

- And repeat...
