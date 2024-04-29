---
weight: 1
bookFlatSection: true
title: "6. Clone GitHub Repository"
---

# Clone GitHub Repository

Once you have read access to the course repository, you would need to clone the repository to your local machine.

Before we can do that, we need to setup your local machine's authentication with Github.

There are many ways to do this.

## GitHub Authentication Option 1: SSH

Follow the official docs to setup SSH authentication:

1. https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
2. https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

Using SSH keys is the preferred method by most companies in the industry as it is more secure by making use of public key cryptography. It would be a good chance for you to learn how to do this if you haven't before.

The idea is that you would upload a "public" key to Github and you keep a "private" key in your machine. That means if you leak your public key, it is very difficult for an attacker to brute force and crack your private key (assuming you keep your private key safe and secure). At the time of writing, brute forcing a key of 4096 bits will take years that can even take longer than our lifetimes in this world.

With this method, clone the repository using the ssh method:

```sh
$ git clone git@github.com:Data-Engineer-Camp/<yyyy><mm>-bootcamp.git
```

## GitHub Authentication Option 2: Personal access tokens

Follow the official docs:

1. https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens

This is the simplest and easiest way to manage authentication with Github. However, you should treat your access tokens as passwords because if it gets leaked, an attacker would have full access to your account.

This is the least preferred method, only do this if you are having issues with the previous option.

With this method, clone the repository using the https method:

```sh
$ git clone https://github.com/Data-Engineer-Camp/<yyyy><mm>-bootcamp.git
Username: YOUR_USERNAME
Password: YOUR_PERSONAL_ACCESS_TOKEN
```

## Pulling updates from the repo

After every lecture, we will be uploading the solved student solutions.

To pull updates from the repository:

```sh
git pull origin main
```

{{< button relref="/docs/5-setup-github" >}}&laquo; Previous{{< /button >}} {{< button relref="/docs/7-intro-presentation" >}}Next &raquo;{{< /button >}}
