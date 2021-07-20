# Build.sh

If you're using the [Smoke Installer Dev-Tools](https://github.com/smoke_installer/dev-tools) you don't need to worry
about this.

In your game's main directory add a file called ``build.sh`` it will compile and move your game. It will have one 
argument passed to it, and it's the user's password. If you think it isn't safe to send the user's password to this 
script, most of every game's code will be reviewed especially this file so it can be trusted.

This is the [build.sh](https://github.com/smoke-installer/hello-smoke-installer/blob/master/build.sh) from the PyGame
Smoke Installer example
