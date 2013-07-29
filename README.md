codebridge-za.github.io
=======================

The codebridge.co.za website runs off Jekyll. After installation of Jekyll to
start the website simply run:

	jekyll serve --watch

## Getting set up with Vagrant

If you have any issues using Jekyll, we have a Vagrant configuration that will 
get you up and running without any issues. After installing 
[Vagrant](http://www.vagrantup.com/) just run

  vagrant up

The first run might take a few minutes as Vagrant downloads Ubuntu (Precise 64-bit), installs jekyll and any dependencies. Finally, Vagrant starts Jekyll on port 4000 by running `jekyll serve --watch`, which will also reload any changes you make.

Visit http://localhost:4000/ in a web browser to view the site :)

You can get shell access through the following command

	vagrant ssh

