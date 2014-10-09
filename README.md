hubot-suggest
=============
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/hassaku/hubot-suggest?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Enables hubot to suggest commands when not found.

## Installation

* Run the `npm install` command.

```
$ npm install hubot-suggest
```

* Add the following code in your `external-scripts.json` file.

```
["hubot-suggest"]
```

## Sample Interaction

```sh
Hubot> Hubot youtobe me penguin
Hubot> Could not find command 'hubot youtobe me penguin'.
Maybe you meant 'Hubot youtube me' or 'Hubot time' or 'Hubot the rules'.
Run `Hubot help` for more commands.
```
