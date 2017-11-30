# Atomic Reactor Toolkit

A framework for building atomic design systems.

## Quick Start
You can simply clone this repo and run `npm run local` in the cloned directory or install via the Atomic Reactor CLI.


### Install Via Atomic Reactor CLI
1. Globally install the Atomic Reactor CLI:
```sh
$ npm install -g atomic-reactor-cli
```

2. Change directory to the folder where you want to install a new Toolkit:
```sh
$ cd /Development/MyProject
```

3. Run the install command
```sh
$ arcli kit:install
```
> You will be prompted for an optional username and password which can be used to secure the toolkit with [Basic Authentication](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication). If you do not wish to secure your butter URL simply press enter/return and skip the prompts.

4. Launch the Toolkit:
```sh
$ npm run local
```

The Toolkit should now be running in your browser and watching for changes to project files. The default url is:
`http://localhost:3000`

> Head over to the [docs](https://github.com/Atomic-Reactor/CLI) for a deeper dive
