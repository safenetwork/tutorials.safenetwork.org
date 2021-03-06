# Email app

In this tutorial, you will learn how to build **an email app that works entirely on the SAFE Network**!

Instead of relying on an email service provider such as Gmail, or going through the trouble of running your own mail server, you can use the SAFE Network to build dynamic applications such as email and messaging apps.

The emails you send using **SAFE Mail Tutorial** are encrypted using the public [encryption key](https://api.safedev.org/low-level-api/appendable-data/encryption-key/) of the recipient. This means that only the recipient of an email is able to read its content. This example app demonstrates the usage of [private appendable data](https://api.safedev.org/low-level-api/appendable-data/).

#### Contents

<!-- toc -->

![Inbox page](img/inbox-page.png)

## Overview

This tutorial will showcase how to:

- [Fetch email data](fetch-email-data.md)
- [Create an email ID](create-an-email-id.md)
- [Send an email](send-an-email.md)
- [Refresh the inbox folder](refresh-the-inbox-folder.md)
- [Save an email](save-an-email.md)
- [Delete an email](delete-an-email.md)

### SAFE APIs

You will learn about the following APIs:

- [Authorization](https://api.safedev.org/auth/)
- [NFS](https://api.safedev.org/nfs/)
- [Structured Data](https://api.safedev.org/low-level-api/structured-data/)
- [Appendable Data](https://api.safedev.org/low-level-api/appendable-data/)
- [Data Identifier](https://api.safedev.org/low-level-api/data-id/)
- [Immutable Data](https://api.safedev.org/low-level-api/immutable-data/)
- [Cipher Options](https://api.safedev.org/low-level-api/cipher-options/)

#### External libraries

- [React](https://facebook.github.io/react/)
- [Redux](http://redux.js.org/)
- [React Router](https://github.com/ReactTraining/react-router)

## Source code

[Browse **the source code of the SAFE Mail Tutorial** on GitHub](https://github.com/maidsafe/safe_examples/tree/master/email_app).

[electron-react-boilerplate](https://github.com/chentsulin/electron-react-boilerplate) was used as a starting point.

### Binaries

[Download **SAFE Mail Tutorial v0.1.2** on GitHub](https://github.com/maidsafe/safe_examples/releases/tag/0.9.0).

Since this app is built using [Electron](http://electron.atom.io/), it can be distributed as a desktop app (Windows, OS X and Linux).

### Building from source

#### Requirements

##### 1. SAFE Launcher

Start [SAFE Launcher v0.10.0](https://github.com/maidsafe/safe_launcher/releases/tag/0.10.0) and log in.

##### 2. Node.js

Make sure you have Node.js v6 (LTS).

```
node --version
```

There are many ways to install Node.js. See [nodejs.org](https://nodejs.org/en/download/) for more info.

#### Setup

##### 1. Clone [this GitHub repository](https://github.com/maidsafe/safe_examples)

```
git clone https://github.com/maidsafe/safe_examples.git
```

If you don't have Git installed, you can download it from [git-scm.com](https://git-scm.com/downloads).

##### 2. Install the dependencies

```
cd safe_examples/email_app && npm install
```

##### 3. Start the app

```
npm run dev
```
