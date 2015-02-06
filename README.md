# ckupdate-demo

Demonstrates the use of the [ckupdate](https://github.com/ComponentKitchen/ckupdate) prototype extension that allows npm to install web components and other front-end libraries.

This project is a modified fork of the [source](https://github.com/JanMiksovsky/printable-wall-calendar) for
[printable-wall-calendar](http://janmiksovsky.github.io/printable-wall-calendar), a simple
web components-based application. The original source uses Bower to install components.
This fork eliminates the need for Bower, allowing the app to be installed
just with npm and the ckupdate extension.

Dependencies in the package.json file point to forks of various web component projects. These forks are essentially the same
as the original web component repos. The only change has been the addition of a package.json manifest (or modification of an
existing one), and the use of the "flatten" keyword. That keyword instructs ckupdate to flatten the dependency.

##Installation

Once you have the [ckupdate](https://github.com/ComponentKitchen/ckupdate) tool installed, you can install this demo
app with just:

    npm install ComponentKitchen/ckupdate-demo

Alternately:

    git clone git@github.com:ComponentKitchen/ckupdate-demo
    cd ckupdate-demo
    npm install

##Viewing the result

Launch index.html under a local web server.


