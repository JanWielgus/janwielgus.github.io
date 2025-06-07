---
layout: post
title:  "How to setup GitHub Credential Manager on Ubuntu"
date:   2025-06-07 15:12:00 +0200
excerpt:
    "How to setup GitHub Credential Manager on Ubuntu"
---

My recommendation is to clone Git repositories using HTTPS instead of SSH. To make that git don't ask for username and password each time you want to communicate with the remote, use GitHub Credential Manager.

This is how to setup it on Ubuntu Linux:

## Installation

Install git if you already haven't. (`sudo apt install git`).

Download GitHub Credential Manager.<br>
Go to https://github.com/git-ecosystem/git-credential-manager/releases, and here choose latest `gcm-linux_amd64` with `.deb` extension.

Open directory where you downloaded the file in Ubuntu terminal. Then run:
```
sudo apt install ./<.deb file>
```
I had some warnings, but everything worked after all.

## Setting up

First run. You don't have to provide any input.
```
git credential-manager configure
```

Then tell git to use credential manager:
```
git config --global credential.credentialStore secretservice
```

## Finishing

You are all set up! Next time, when you will use a command, that will require authentication, you can log in to GitHub by transfering a request to the browser, and finishing there. You will know what to do.

Then you can forget about authentication. GitHub Credential Manager will do that for you!
