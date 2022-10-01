# [My portfolio website](https://mihsamusev.github.io/)

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)

All credit goes to the creators and contributors of [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes)

## Build tools (Linux)

Install Jekyll and dependencies like [here](https://jekyllrb.com/docs/installation/ubuntu/).

```sh
sudo apt-get update
sudo apt-get install ruby-full build-essential zlib1g-dev
```

Add path variables for Ruby Gems:

```sh
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc # execute chages in .bashrc
```

Finally, install Jekyll and Bundler:

```sh
gem install jekyll bundler
```

## How to build and view locally

Make sure all the themes are installed

```sh
bundle install
```

The follwing command will host the static page on localhost and changes will be rendered on refresh.

```sh
bundle exec jekyll serve
```
