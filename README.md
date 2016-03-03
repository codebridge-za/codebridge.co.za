codebridge-za.github.io
=======================

This website is generated using [Jekyll](https://jekyllrb.com/), with a [Bootstrap 3](https://getbootstrap.com/) framework, and is hosted by Github that points to a custom domain. We welcome any and all contributions, be sure to check out if there are any pending [issues](https://github.com/codebridge-za/codebridge-za.github.io/issues). 

## Getting started
### Jekyll

Once you've cloned a copy of the git, open a terminal from the project's directory  and type the following:

    jekyll serve

Open a browser and visit `http://localhost:4000` to preview the site. If you're new to Jekyll (or Ruby), you'll need to follow their simple [installation guide](http://jekyllrb.com/docs/home/).

### Vagrant

We also have a [Vagrant](http://www.vagrantup.com/) configuration that will get you up and running without having to install Jekyll first. After [installing](https://docs.vagrantup.com/v2/installation/index.html) Vagrant just run this command from this project's directory:

    vagrant up

Your first run might take a few minutes, as the configuration will download [Ubuntu (Precise Pangolin 64-bit)](http://releases.ubuntu.com/12.04/), then install Jekyll and any dependencies. 

Once complete, Vagrant will start Jekyll by running `jekyll serve`. You can then see a preview at `http://localhost:4000/` in a web browser.

You can get shell access through the following command

    vagrant ssh

## Framework changes

Please **do not** contribute with an updated version of Bootstrap or jQuery, as we need to support IE 8 and beyond. The fourth version of Bootstrap has dropped IE 8/9 support and jQuery 2x does not work on older browsers.

Our base users are South Africans, at [least 22%](http://gs.statcounter.com/#browser-ZA-monthly-201411-201511) of the connected population still use IE.