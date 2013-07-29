codebridge-za.github.io
=======================

To develop on the codebridge.co.za Jekyll site, simply run:

	vagrant up

The first run might take a few minutes as Vagrant downloads Ubuntu (Precise 64-bit), installs jekyll and any dependencies. Finally, Vagrant starts Jekyll on port 4000 by running `jekyll serve --watch`, which will also reload any changes you make.

Visit http://localhost:4000/ in a web browser to view the site :)

## What about shell access?

	vagrant ssh

## Requirements

 - [Vagrant](http://www.vagrantup.com/)
