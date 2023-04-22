# concept3racing website

## Local Setup / Testing

These instructions are for Ubuntu 22.04.

Install ruby, jekyll, and bundler
```shell
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/.local/gems' >> ~/.profile
echo 'export GEM_HOME="$HOME/.local/gems"' >> ~/.profile
echo 'export PATH="$HOME/.local/gems:$PATH"' >> ~/.profile
source ~/.profile
gem install jekyll bundler
bundle install
```

Build the website and host locally
```shell
bundle exec jekyll serve --livereload
```

Browse to http://localhost:4000

## Other OS Instructions

https://jekyllrb.com/docs/installation/#guides
