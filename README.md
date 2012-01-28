# gitfinger

A simple Ruby gem that lets you finger GitHub users.

![screen](https://github.com/danchoi/gitfinger/raw/master/screenshots/gitfinger.png)

## Usage

    gitfinger [GitHub username] [options]

## Options

    Specific options:
        -s, --sort FIELD                 Sort on FIELD; you can try to abbreviate FIELD
        -r, --reverse                    Reverse default order
        -H, --no-header                  Suppress header and prefix repo name with user
        -h, --help                       Show this message
        -v, --version                    Show version

## Examples

Sort repos by number of issues, from most to least:

    gitfinger thoughtbot -si

Sort repos by number of watchers, from most to least:

    gitfinger rails -sw

Sort repos by date of last push, starting from most recent:

    gitfinger rails -sp

## Install

    gem install gitfinger


