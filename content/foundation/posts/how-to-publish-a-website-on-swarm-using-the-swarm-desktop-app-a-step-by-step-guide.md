+++
banner = "/uploads/how-to_website.png"
images = [ "/uploads/how-to_website.png" ]
categories = [ "Tutorials" ]
date = 2023-03-28T22:00:00.000Z
description = "TL;DR: This guide will walk you through the process of publishing a website on Swarm using the Swarm Desktop App. You’ll learn how to install the app, fund your account, upload your website, and connect an ENS domain for a user-friendly experience. By following these steps, you’ll be able to host a censorship-resistant website on decentralised storage and make it easily accessible for users."
references_and_footnotes = [ ]
title = "How to Publish a Website on Swarm Using the Swarm Desktop App: A Step-by-Step Guide"
_template = "post"
+++

**TL;DR:** This guide will walk you through the process of publishing a website on Swarm using the [Swarm Desktop App](https://desktop.ethswarm.org/). You’ll learn how to install the app, fund your account, upload your website, and connect an ENS domain for a user-friendly experience. By following these steps, you’ll be able to host a censorship-resistant website on decentralised storage and make it easily accessible for users.

## Introduction to the Swarm Desktop App

Swarm Desktop App serves as a personal access point to the Swarm network, enabling interaction with content hosted on Swarm. The app allows you to:

- Store (upload and download) files to decentralised storage (Swarm)
- Securely and privately send files to others
- Easily host and manage HTML websites.

## Install Swarm Desktop App and Fund Your Account

First, download and install the [Swarm Desktop App](https://desktop.ethswarm.org/). Next, add xDAI (transaction fees) to your Node Wallet address. If you possess xBZZ (storage fees), you can deposit it alongside the xDAI. Otherwise, you can exchange your xDAI for xBZZ using the Swarm Desktop app.

Follow these steps to deposit funds:

1. **Launch the Swarm Desktop App** and go to the **Account** section in the left menu.
2. **Transfer xDAI** to your node wallet address. For safety, we suggest sending no more than 5 to 10 xDAI.
3. After funding your wallet, click the **Top Up Wallet** button on the right side of the screen.
4. Select the **Use xDAI** option.
5. Verify your xDAI balance and click **Proceed**.
6. Specify the amount of xDAI to convert to xBZZ and click **Swap Now**.
7. Your Node Wallet address will be credited with xBZZ.

![](https://i.imgur.com/CALz1UF.gif)

Your node address is now funded with xDAI and xBZZ. However, to upload data on Swarm, you will need to transfer your funds to the Chequebook contract address.

Follow these steps:

1. Go to the **Account** section in the left menu.
2. Select the **Chequebook** tab in the top menu.
3. Click the **Deposit** button.
4. **Specify the amount of xBZZ** to deposit into your Chequebook, which will be used for storage costs.

## Publishing Your Website on Swarm

To publish your website on Swarm, follow these steps:

1. Navigate to the **Files** tab.
2. Click the **Add Website** button.
3. **Select your website folder**. NOTE: The index.html file should be in the root folder.
4. **Purchase a Postage Stamp** to publish your page. NOTE: Postage stamps cover storage costs for a specified duration.
5. **Upload the website to your Node**.

NOTE: If you plan to update your website in the future please check the last section in the blogpost

![](https://i.imgur.com/KYhL83L.gif)

[https://api.gateway.ethswarm.org/bzz/6843d3be17364ea0620011430e4db2a26ff781da478493a02d6eb5aae886b8ae/](https://api.gateway.ethswarm.org/bzz/6843d3be17364ea0620011430e4db2a26ff781da478493a02d6eb5aae886b8ae/ "https://api.gateway.ethswarm.org/bzz/6843d3be17364ea0620011430e4db2a26ff781da478493a02d6eb5aae886b8ae/")

**Please note that if you’re planning to update your website in the future, be sure to check out the last section of the blog post.**

## Connecting an ENS Domain to Your Website

Associating your ENS domain with a Swarm hash generates a memorable, user-friendly identifier for your website, allowing users to easily locate and access your website without having to recall a lengthy, complex Swarm hash.

Initially, you’ll need to register your domain name. To register and manage your ENS domain, you can use the [ENS Domains Dapp](https://app.ens.domains/) along with the [MetaMask](https://metamask.io/) browser extension.

After registering your name and connecting MetaMask to the relevant Ethereum account, set the resolver to use the public ENS if you haven’t already.

1. Navigate to **My Names** and select the name you want to link to your Swarm content.
2. Click on **ADD/EDIT RECORD**.
3. From the “add record” dropdown menu, select **Content**.
4. **Enter your Swarm Hash**, beginning with “bzz://” and click “Save.”

![](https://i.imgur.com/JlhCVMz.gif)

Your website is now available on:

[https://api.gateway.ethswarm.org/bzz/swarm-devrel.eth/](https://api.gateway.ethswarm.org/bzz/swarm-devrel.eth/ "https://api.gateway.ethswarm.org/bzz/swarm-devrel.eth/")

## Update the Website: Set up and update a feed

Swarm feeds allow you to easily create a permanent address for your content stored on Swarm that you can update at any time.

If you plan to update your website in the future, it’s recommended that you set up a “Feed” before uploading your website to Swarm. This way, the Swarm Hash connected to your ENS domain will stay the same, even as you change the content behind that hash. This will enable you to update your website’s content without changing the Swarm Hash and incurring Ethereum transaction costs each time you do so.

Set up a Feed:

1. Navigate to to **Account**
2. Click on **Feeds** in the top menu
3. Clik on **Create New Feed**
4. Define **Identity name**
5. And click **Create Feed**.

Upload Website on Swarm and connect it to the Feed:

1. Navigate to to **Account**
2. Click on **Feeds** in the top menu
3. Choose the **Feed** you want to update
4. Click **View Feed Page**
5. Click the **Add Website** button.
6. **Select your website folder**. NOTE: The index.html file should be in the root folder.
7. **Add Postage Stamp** to publish your page. NOTE: Postage stamps cover storage costs for a specified duration.
8. **Upload the website to your Node**.
9. Connect Feed hash to ENS domain as described above.

![](https://i.imgur.com/oCNQejB.gif)

In conclusion, this step-by-step guide has provided you with a comprehensive understanding of how to publish and update a website on the Swarm network using the Swarm Desktop App. By following these instructions, you can now leverage the benefits of decentralised storage, maintain a censorship-resistant website, and create a user-friendly experience by connecting your site to an ENS domain.
