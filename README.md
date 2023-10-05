<h1 align="center">
<img src="https://64.media.tumblr.com/5ce3b7edf9c54d05f09262c99b308aba/ae196e17681cc07a-37/s1280x1920/adaab7c91f9754671fac1cc7c2e545a333784ffc.pnj" alt="honsecoin" width="300"/>
<br/><br/>
Honsecoin Core
</h1>

<div align="center">

## Usage 💻

To start your journey with Honsecoin Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Honsecoin Core is self-documenting. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Such ports

Honsecoin Core by default uses port `22556` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `22555` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   22556 |   44556 |   18444 |
| RPC      |   22555 |   44555 |   18332 |

## Ongoing development - Moon plan 🌒

Honsecoin Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

[Honse subreddit](https://www.reddit.com/r/honse/)

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

## Contributing 🤝

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of Honsecoin Core.

## Communities 🚀🍾

You can join the communities on different social media.
To see what's going on, meet people & discuss, find the latest meme, learn
about Honsecoin, give or ask for help, to share your project.

Here are some places to visit:

* [Dogecoin subreddit](https://www.reddit.com/r/honse/)

## Very Much Frequently Asked Questions ❓

Do you have a question regarding Hoecoin? An answer is perhaps already in the
[FAQ](doc/FAQ.md)

## License - Much license ⚖️
Honsecoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
