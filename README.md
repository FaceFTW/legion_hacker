# legion_hacker
Forked from [cbbuntz/legionhacker](https://github.com/cbbuntz/legion_hacker)

A collection of terminal tools for simple text colorization, TUI design and animation. May also give you hacking superpowers.


![legion hacker screeenshot](https://i.imgur.com/tLN4jOO.png)

## Features / Plans:

* Create a CLI Menu to various hacking options
* Allow user control of program flow or automated flow

## Get Started

Launch the `hack` executable:

```
$ ruby bin/hack
```

### Development

To install development dependencies:
```
$ bundle install
```

Linting and style check can be done using `rubocop` via `rake`

```
$ rake
```

### Troubleshooting

If you get errors, ensure that you have the necessary dependencies
```
$ gem list --local | grep bundler || gem install bundler
$ gem list --local | grep rake || gem install rake
$ bundle install
```

External Linux packages are needed for ```bundler``` to install the dependencies. If you get an error when running bundler, use this command on your distro:

####Ubuntu/Debian/DPKG
```clickhouse
$ sudo apt-get install make gcc ruby-dev
```

####Fedora 
```clickhouse
$ dnf install make gcc ruby-dev
```
OR
```clickhouse
$ yum install make gcc ruby-dev
```

####Arch (btw I use arch lol)
```clickhouse
$ #Will update just lazy xD
```