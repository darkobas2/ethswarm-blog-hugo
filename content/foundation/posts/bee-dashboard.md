+++
banner = ""
images = [ "" ]
categories = [ "Development updates" ]
date = 2021-04-29T04:00:00.000Z
description = """
The Bee Dashboard is a web app that can help you set up your Bee node. It connects to your locally running node, checks the status of different API endpoints, and offers troubleshooting.

"""
references_and_footnotes = [ ]
title = "Bee Dashboard"
_template = "post"
+++

**_TLDR; Try out_** [**_Bee Dashboard_**](https://github.com/ethersphere/bee-dashboard) **_which can help you set up your Bee node, monitor its status, and perform actions like uploading files and cashing out cheques. Special thanks to our contributors_** [**_matmertz25_**](https://github.com/matmertz25)**_,_** [**_centerorbit_**](https://github.com/centerorbit) **_, and_** [**_tmm360_**](https://github.com/tmm360)

> _Good infrastructure is something that you use without even thinking about it. It just works._

At Swarm, we are striving to build just that. Good infrastructure. But this is a process, and just as it took skilled engineers to set up wireless networks 20 years ago, we too are at a stage where starting up a Bee node entails several steps, with instructions differing greatly between operating systems. We are extremely grateful to everyone who has already put their time and effort into running one of the 51,000 Bee nodes. Just as we announced the [Rise of the Bee airdrop](https://medium.com/ethereum-swarm/swarm-is-airdropping-1-000-000-bzz-bd3b706918d3), we were quickly reminded that setting up the nodes is not as user-friendly as we would like it to be. We always wanted to build a UI for Swarm, but as we had other more pressing tasks, we decided to offer it to the community as a bounty. The end result was a rather nice surprise.

# What is it?

The Bee Dashboard is a web app that can help you set up your Bee node. It connects to your locally running node, checks the status of different API endpoints, and offers troubleshooting.

![](/uploads/1-7.webp)

_Bee Dashboard can help you to troubleshoot your Bee node_

Once your node is working, the status page will show information about your node such as the version of your Bee node, Ethereum Address, or your PSS public key.

![](/uploads/2-8.png)

_Once your node is running properly, you can see details like your Ethereum address or PSS public key_

This is all we asked for when we proposed the bounty. However, [matmertz25](https://github.com/matmertz25) did not stop there and built extra functionality like uploading and downloading files, exploring the peer connections, and even managing the node accounting.

![](/uploads/3-5.png)

_With Bee Dashboard, you can upload and download files_

![](/uploads/4-6.png)

_In the Peers tab, you will see how your node is connected to the network_

The accounting feature is especially attractive for everyone participating in the [Rise of the Bee airdrop](https://medium.com/ethereum-swarm/swarm-is-airdropping-1-000-000-bzz-bd3b706918d3). You can now use a user interface to see your peer balances and cash out any outstanding cheques.

![](/uploads/5-4.png)

_The Accounting page helps you manage the financial part of Bee. You can cash out your earnings from other peers_

**How do I run it?**

For now, you will still need a terminal. Follow the install, build, and serve instructions on the official [**Bee Dashboard**](https://github.com/ethersphere/bee-dashboard#install--build) github page.

# What is the project’s future?

The ultimate goal of the project is to be a downloadable app that installs and sets up your Bee node and helps you keep it up-to-date. We are heading there in three stages.

- [**0.1.0**](https://github.com/ethersphere/bee-dashboard/milestone/1) **— Web app:** This is where we are right now. Users can download and run this in their web browser.
- [**0.2.0**](https://github.com/ethersphere/bee-dashboard/milestone/2) **— Electron app:** A downloadable app that can run on linux, mac, or windows and connects to a separately running Bee node.
- [**0.3.0**](https://github.com/ethersphere/bee-dashboard/milestone/2) **— Bee Desktop:** A downloadable app that can install Bee and helps you to configure it.

Other notable features are internationalization or being able to manage several Bee nodes at once.

# How can I help?

From the start, this has been a community project, built by community members and solving issues our users have. We would like to keep it that way.

1. Try it out.
2. Tell us how you like it. What doesn’t quite work for you? What can we improve? What you would like to do that the app is missing?
3. Pick one of the issues on github ([Help Wanted](https://github.com/ethersphere/bee-dashboard/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) issues are a good start).
4. (soon) Do you speak a language we don’t? Help us translate the app.

A big thank you to our contributors — [matmertz25](https://github.com/matmertz25), [centerorbit](https://github.com/centerorbit), and [tmm360](https://github.com/tmm360).
