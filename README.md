![](/assets/screenshot-ui.png)

# <a href='http://botpress.io'><img src='https://httpsimage.com/img/botpress-logo-120.png' height='60'></a>

Botpress is an open-source bot creation tool written in Javascript. It is powered by a rich set of open-source (and proprietary) modules built by the community. Botpress is on a mission to make bots ubiquitous and profitable for everybody.

## Installation

Botpress requires [node](https://nodejs.org) (version >= 4.2) and uses [npm](https://www.npmjs.com) as package manager.

```
npm install -g botpress
```

## Usage

Creating a bot is simple, simply run [`botpress init`](/docs/cli-reference.md#init) inside an empty directory:

```
mkdir my-bot && cd my-bot
botpress init
```

Once your bot is created, you may [start](/docs/cli-reference.md#start--s) it:

```
botpress start
```

This will provide you with a web interface available at **`http://localhost:3000`**

You then need to install some modules. You can do so directly in the web interface, or using the [`botpress install`](/docs/cli-reference.md#install--i) CLI command:

```
botpress install messenger
```

For a more detailed usage guide, please read the [Getting Started Guide](/docs/getting-started.md).

## Examples

There's a [video on YouTube](TODO) that shows how to create a Hello World Messenger Bot in under 45 seconds.

- [Hello World Messenger Bot](TODO)
- Todolist Messenger Bot _(soon)_
- Scheduling Messages _(soon)_
- Bot Analytics _(soon)_

Many more code examples are available in the **[Examples repository](https://github.com/botpress/botpress-examples)**

## Documentation

- [Getting Started Guide](/docs/getting-started.md)
- [Advanced Topics](/docs/advanced-topics.md)
- [CLI Reference](/docs/cli-reference.md)
- [Core Reference](/docs/core-reference.md)

## Community

There's a [public chatroom](https://gitter.im/botpress/core) where you are welcome to join and ask any question and even help others.

## License

Botpress is dual-licensed under [AGPLv3](/licenses/LICENSE_AGPL3) and the [Botpress Proprietary License](/licenses/LICENSE_BOTPRESS). 

By default, any bot created with Botpress is licensed under AGPLv3, but you may change to the Botpress License from within your bot's web interface in a few clicks.
