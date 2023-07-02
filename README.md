# Dylan's Website

## Prerequisites

Make sure that you have installed Ruby and that its version matches the one in
[.ruby-version](.ruby-version). I recommend using a tool such as
[rbenv](https://github.com/rbenv/rbenv) to do this.

### Debian-based Linux Distributions

```bash
apt update && apt install rbenv
```

### macOS with Homebrew

```bash
brew update && brew install rbenv
```

## Installation

```bash
git clone https://github.com/dylanspag/dylanspag.github.io.git
cd dylanspag.github.io
rbenv install $(cat .ruby-version)
gem install bundler
bundle install
```

## Usage

The following command will serve the website on your local machine at port 4000.
Include the host option if you would like to access the deployment from a remote
machine.

```bash
bundle exec jekyll serve [--host 0.0.0.0]
```

## Licensing

Feel free to use this code to set up your own website on GitHub Pages. See the
[license](LICENSE) for additional details.

