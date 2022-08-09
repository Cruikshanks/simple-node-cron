# Simple Node Cron

[![Licence](https://img.shields.io/badge/Licence-MIT-blue.svg)](https://opensource.org/licenses/MIT)

This is a very basic example of using [node-cron](https://github.com/node-cron/node-cron).

> The node-cron module is tiny task scheduler in pure JavaScript for node.js based on [GNU crontab](https://www.gnu.org/software/mcron/manual/html_node/Crontab-file.html). This module allows you to schedule task in node.js using full crontab syntax.

## Prerequisites

Make sure you already have:

- [Node.js v14.*](https://nodejs.org/en/)

## Installation

First clone the repository and then drop into your new local repo:

```bash
git clone https://github.com/Cruikshanks/simple-node-cron.git && cd simple-node-cron
```

Then install the dependencies

```bash
npm ci
```

## Gotcha

Key thing I overlooked is that this is _based_ on GNU crontab. It does not interact with it. I wasted a certain amount of time running `cron-l` and searching in `/etc/cron.d` for things that don't exist!

## Contributing

Bug reports and pull requests are welcome on GitHub at <https://github.com/cruikshanks/simple-bullmq>.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

> If you don't add a license it's neither free or open!
