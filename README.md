
# TYSLINIO - The Most Powerful Infrastructure for Decentralized Applications




Tyslin is a blockchain forked of EOS platform designed for the real world and recognized as the most performant blockchain platform. It is built for public or private, and permissioned or permissionless blockchain infrastructure. Tyslin is also adaptable to suit a wide range of business needs across industries with rich role-based security permissions and industry-leading throughput. Moreover, it’s designed for secure application processing.
Building on Tyslin follows familiar development patterns and programming languages used by existing non-blockchain applications. This means  developers can create a seamless user experience with development tools they already know and love.




For more information please contact 

info@reactivespace.com



[![Build status](https://badge.buildkite.com/370fe5c79410f7d695e4e34c500b4e86e3ac021c6b1f739e20.svg?branch=master)](https://buildkite.com/TYSLINIO/TYSLINio)

Welcome to the TYSLINIO source code repository! This software enables businesses to rapidly build and deploy high-performance and high-security blockchain-based applications.

Some of the groundbreaking features of TYSLINIO include:

1. Free Rate Limited Transactions
1. Low Latency Block confirmation (0.5 seconds)
1. Low-overhead Byzantine Fault Tolerant Finality
1. Designed for optional high-overhead, low-latency BFT finality
1. Smart contract platform powered by WebAssembly
1. Designed for Sparse Header Light Client Validation
1. Scheduled Recurring Transactions
1. Time Delay Security
1. Hierarchical Role Based Permissions
1. Support for Biometric Hardware Secured Keys (e.g. Apple Secure Enclave)
1. Designed for Parallel Execution of Context Free Validation Logic
1. Designed for Inter Blockchain Communication

## Disclaimer

Block.one is neither launching nor operating any initial public blockchains based upon the TYSLINIO software. This release refers only to version 1.0 of our open source software. We caution those who wish to use blockchains built on TYSLINIO to carefully vet the companies and organizations launching blockchains based on TYSLINIO before disclosing any private keys to their derivative software.

## Official Testnet

[testnet.TYSLIN.io](https://testnet.TYSLIN.io/)

## Supported Operating Systems

TYSLINIO currently supports the following operating systems:  

1. Amazon Linux 2
2. CentOS 7
3. Ubuntu 16.04
4. Ubuntu 18.04
5. MacOS 10.14 (Mojave)

---

**Note: It may be possible to install TYSLINIO on other Unix-based operating systems. This is not officially supported, though.**

---

## Software Installation

If you are new to TYSLINIO, it is recommended that you install the [TYSLINIO Prebuilt Binaries](#prebuilt-binaries), then proceed to the [Getting Started](https://developers.TYSLIN.io/TYSLINio-home/docs) walkthrough. If you are an advanced developer, a block producer, or no binaries are available for your platform, you may need to [Build TYSLINIO from source](https://TYSLINio.github.io/TYSLIN/latest/install/build-from-source).

---

**Note: If you used our scripts to build/install TYSLINIO, please run the [Uninstall Script](#uninstall-script) before using our prebuilt binary packages.**

---

## Prebuilt Binaries

Prebuilt TYSLINIO software packages are available for the operating systems below. Find and follow the instructions for your OS:

### Mac OS X:

#### Mac OS X Brew Install
```sh
brew tap TYSLINio/TYSLINio
brew install TYSLINio
```
#### Mac OS X Brew Uninstall
```sh
brew remove TYSLINio
```

### Ubuntu Linux:

#### Ubuntu 18.04 Package Install
```sh
wget https://github.com/TYSLINio/TYSLIN/releases/download/v2.0.9/TYSLINio_2.0.9-1-ubuntu-18.04_amd64.deb
sudo apt install ./TYSLINio_2.0.9-1-ubuntu-18.04_amd64.deb
```
#### Ubuntu 16.04 Package Install
```sh
wget https://github.com/TYSLINio/TYSLIN/releases/download/v2.0.9/TYSLINio_2.0.9-1-ubuntu-16.04_amd64.deb
sudo apt install ./TYSLINio_2.0.9-1-ubuntu-16.04_amd64.deb
```
#### Ubuntu Package Uninstall
```sh
sudo apt remove TYSLINio
```

### RPM-based (CentOS, Amazon Linux, etc.):

#### RPM Package Install
```sh
wget https://github.com/TYSLINio/TYSLIN/releases/download/v2.0.9/TYSLINio-2.0.9-1.el7.x86_64.rpm
sudo yum install ./TYSLINio-2.0.9-1.el7.x86_64.rpm
```
#### RPM Package Uninstall
```sh
sudo yum remove TYSLINio
```

## Uninstall Script
To uninstall the TYSLINIO built/installed binaries and dependencies, run:
```sh
./scripts/TYSLINio_uninstall.sh
```

## Documentation
1. [NodTYSLIN](http://TYSLINio.github.io/TYSLIN/latest/nodTYSLIN/)
    - [Usage](http://TYSLINio.github.io/TYSLIN/latest/nodTYSLIN/usage/index)
    - [Replays](http://TYSLINio.github.io/TYSLIN/latest/nodTYSLIN/replays/index)
    - [Chain API Reference](http://TYSLINio.github.io/TYSLIN/latest/nodTYSLIN/plugins/chain_api_plugin/api-reference/index)
    - [Troubleshooting](http://TYSLINio.github.io/TYSLIN/latest/nodTYSLIN/troubleshooting/index)
1. [ClTYSLIN](http://TYSLINio.github.io/TYSLIN/latest/clTYSLIN/)
1. [KTYSLINd](http://TYSLINio.github.io/TYSLIN/latest/kTYSLINd/)

## Resources
1. [Website](https://TYSLIN.io)
1. [Blog](https://medium.com/TYSLINio)
1. [Developer Portal](https://developers.TYSLIN.io)
1. [StackExchange for Q&A](https://TYSLINio.stackexchange.com/)
1. [Community Telegram Group](https://t.me/TYSLINProject)
1. [Developer Telegram Group](https://t.me/joinchat/EaEnSUPktgfoI-XPfMYtcQ)
1. [White Paper](https://github.com/TYSLINIO/Documentation/blob/master/TechnicalWhitePaper.md)
1. [Roadmap](https://github.com/TYSLINIO/Documentation/blob/master/Roadmap.md)

<a name="gettingstarted"></a>
## Getting Started
Instructions detailing the process of getting the software, building it, running a simple test network that produces blocks, account creation and uploading a sample contract to the blockchain can be found in the [Getting Started](https://developers.TYSLIN.io/welcome/latest/getting-started) walkthrough.

## Contributing

[Contributing Guide](./CONTRIBUTING.md)

[Code of Conduct](./CONTRIBUTING.md#conduct)

## License

TYSLINIO is released under the open source [MIT](./LICENSE) license and is offered “AS IS” without warranty of any kind, express or implied. Any security provided by the TYSLINIO software depends in part on how it is used, configured, and deployed. TYSLINIO is built upon many third-party libraries such as WABT (Apache License) and WAVM (BSD 3-clause) which are also provided “AS IS” without warranty of any kind. Without limiting the generality of the foregoing, Block.one makes no representation or guarantee that TYSLINIO or any third-party libraries will perform as intended or will be free of errors, bugs or faulty code. Both may fail in large or small ways that could completely or partially limit functionality or compromise computer systems. If you use or implement TYSLINIO, you do so at your own risk. In no event will Block.one be liable to any party for any damages whatsoever, even if it had been advised of the possibility of damage.  

## Important

See [LICENSE](./LICENSE) for copyright and license terms.

All repositories and other materials are provided subject to the terms of this [IMPORTANT](./IMPORTANT.md) notice and you must familiarize yourself with its terms.  The notice contains important information, limitations and restrictions relating to our software, publications, trademarks, third-party resources, and forward-looking statements.  By accessing any of our repositories and other materials, you accept and agree to the terms of the notice.
