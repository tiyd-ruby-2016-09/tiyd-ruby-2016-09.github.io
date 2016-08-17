---
layout: default
---

## Mac Setup

As soon as possible after receiving your Mac, run through the following steps. If you've done a lot of your own configuration, some of these steps may have to change.

<script>
var name = 'bryce';
var domain = 'theironyard.com';
var address = name + '@' + domain;
document.write('<p>If you run in to ANY PROBLEMS, send me an e-mail at <a href="mailto:' + address + '">' + address + '</a>.</p>');
</script>
<noscript>Enable javascript to see my email!</noscript>

Again, we want to have all of these kinks worked out in advance, so PLEASE e-mail if things don't work as described below.

* Install Atom
  * Download Atom from [the Atom website](https://atom.io/).
  * Install and run it.
  * Click on the "Atom" option in your menu bar (all the way in the upper-left of your screen) and choose "Install Shell Commands."

<!-- break -->

* Install Google Chrome
  * Download Chrome from [the Chrome download page](https://www.google.com/intl/en/chrome/browser/).
  * Install and run it.

<!-- break -->

* Install XCode Command Line Tools
  * Go to the [Apple Developer Downloads site](https://developer.apple.com/downloads/).
  * You will have to register.
  * If you are running Yosemite, look for "Command Line Tools (OS X 10.10) for Xcode - Xcode ..."
  * If you are running El Capitan, look for "Command Line Tools (OS X 10.11) for Xcode - Xcode ..."
  * Download it, run it, and follow all the prompts.

<!-- break -->

* Install Homebrew
  * Open up Terminal.
  * Run `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  * Run `brew doctor`

<!-- break -->

* Install rbenv & ruby-build
  * Open up Terminal (or if you've still got it open, keep using it).
  * `brew install ruby-build rbenv`
  * `echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile`

<!-- break -->

* Install ruby 2.3.1
  * Close and reopen Terminal.
  * `rbenv install 2.3.1`
  * Go and get some coffee. That last one will take a while.
  * `rbenv global 2.3.1`
  * Close and reopen Terminal.
  * Run `which ruby`. If you see a path starting with `/usr/bin/`, get a TA or instructor to help you.

<!-- break -->

* Install git
  * In Terminal
  * `brew install git`
  * `git config --global push.default simple`
  * `git config --global credential.helper osxkeychain`

<!-- break -->

* Install Heroku Toolbelt
  * Download the Toolbelt from [this page](https://toolbelt.heroku.com/).
  * Run it and follow the install steps.
  * Open Terminal and run `heroku login`. Enter your Heroku credentials when asked.

<!-- break -->

* Add the following applications to your Dock
  * Atom
  * Chrome
  * Terminal
