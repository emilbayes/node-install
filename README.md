# node-install

Extremely simple node install script
It is available through [bashkit](https://github.com/mafintosh/bashkit)

	bashkit install mafintosh/node-install

Or using this one-line install

	 curl -s https://raw.github.com/mafintosh/node-install/master/install | bash && . $(bashkit rc)

It is easy to use

	node-install 0.10.10 # installs node 0.10.10
	node-install 0.8.24  # installs node 0.8.24

It also features autocompletion!

	node-install <tab><tab> # prints all available versions

It is licensed under MIT