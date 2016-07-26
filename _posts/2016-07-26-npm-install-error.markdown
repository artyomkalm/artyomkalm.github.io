---
layout: post
title:  "NPM Install error with Phoenix Framework"
date:   2016-07-26 22:53:17 +0300
categories: jekyll update
---
One of the ways to install the latest version with nvm. For me it was very helpful. At first remove old version.

    sudo apt-get remove nodejs
And install the latest one

    wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash
    nvm install 5.0
    nvm use 5.0