<h1 align="center">UnbelievaBoat API Wraper</h1><br>
<p align="center">
  <a href="https://unb.pizza/">
    <img alt="Unb" title="Unb" src="https://i.imgur.com/tUiCsY5.jpg" width="400">
  </a>
</p>

<p align="center">
  A Go library for the UnbelievaBoat Discord bot API.<br/>
  By <a href="https://bailey.guru/">Bailey</a>
</p>

<p align="center">
  <a href="https://unb.pizza/">
    Website
  </a>
|
  <a href="https://discordapp.com/invite/YMJ2dGp">
    Discord
  </a>
</p>

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Feedback](#feedback)
- [Install Process](#Install-process)
- [Acknowledgments](#acknowledgments)

## Introduction

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Discord](https://img.shields.io/badge/Chat_On-Discord-008080.svg?style=flat-square)](https://discordapp.com/invite/YMJ2dGp)

The UnbelievaBoat API library is an importable package to make using the UnbelievaBoat API easier to use within Go. Although updates may be few and far, all new features are added as they are released as I talk to the developer of the bot and I am made aware of upcoming changes. **PRs, bug reports and feature requests are welcome!**

Version 1 ([`/v1`](https://github.com/BaileyJM02/unb-api-go/tree/master/v1)) uses version 1 of the UnbelievaBoat API and should be imported as `github.com/BaileyJM02/unb-api-go/v1`, more on the install process [here](#install-process). This is allows for the second version of the api to be installed as `github.com/BaileyJM02/unb-api-go/v2` etc. upon release.

## Features

A few of the things you can do with **unb-api-go**:

* Connect to the UnbelievaBoat API
* See user balance
* See guild leaderboard
* Set custom http.Client
* And more...

## Feedback

Feel free to send me feedback on [Twitter](https://twitter.com/BaileyJM02) or [file an issue](https://github.com/baileyjm02/unb-api-go/issues/new). Feature requests are always welcome. If you wish to contribute, please take a quick look at the [guidelines](./CONTRIBUTING.md)!

If there's anything you'd like to chat about, please feel free to join our [Discord Server](https://discordapp.com/invite/YMJ2dGp) and mention me: `@Bailey#0004`!

## Install Process

> I'm guessing you already have an environment setup.
- `$ go get github.com/BaileyJM02/unb-api-go/v1` to install the wrapper (v1)
- `api := v1.New(token)` to create a new instance, `token` is your token found [here](https://unb.pizza/api/docs)
- `api.GetBalance(guildID, userID)` functions follow the `api` var we created above.

## Acknowledgments

> Nothing here yet.