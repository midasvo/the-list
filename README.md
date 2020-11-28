# the-list
Inspired by a comment on /r/soccer, which inspired a subreddit called /r/SaddestBackflip now turns into a website since people keep having to find different versions of the list

## Features

- Pagination
  - Main page has a pagination widget so not all posts are shown at once
- JSON API
  - Ability to easily retrieve content using GET requests (e.g. by appending '[/index.json](https://list.futbol/items/index.json)' to the url.)

# Contributing

How to start contributing by developing the website, external apps, creating posts, and pitching ideas.

## Add it to the list!

If you want to add something to the list, either setup the development environment, create the post, and create a pull request

OR

Create an issue [here](https://github.com/midasvo/the-list/issues) and a developer will create it for you

## Developing

Requirements:

- Git
- homebrew
- Hugo

The site is built on Hugo, which is a static site generator. Hugo is easily installed using homebrew.

### Installing homebrew

Installing homebrew for [mac and linux](https://brew.sh/)

TODO: installing homebrew for windows (binaries found here: https://github.com/gohugoio/hugo/releases)

### Installing hugo

> brew install hugo

### Cloning the repository

> git clone https://github.com/midasvo/the-list.git

### Running the website

> cd the-list

> hugo server

## Creating a new post

Run the command below to create a new markdown file in 'the-list/content/items/'. This markdown file represents the post, if you run 'hugo server' it will show up in the UI.

> hugo new items/it-was-the-saddest-backflip.md

The initial contents of the file will be something like

> ---

> title: "It Was the Saddest Backflip"

> date: 2020-11-24T19:17:30+01:00

> itemurl: ""

> itemurl_archive: ""

> itemurl_soccer: ""

> itemurl_saddestbackflip: ""

> tags: []

> draft: false

> ---

Change the title, date, and add any itemurls available. 

Add the itemurl's you know

- itemurl: the link to the article
- itemurl_archive: an archived link for if the original is removed
- itemurl_soccer: the link to the /r/soccer thread
- itemurl_saddestbackflip: the link to the /r/saddestbackflip thread

## Creating a pull request

TODO
