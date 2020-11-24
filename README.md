# the-list
Inspired by a comment on /r/soccer, which inspired a subreddit called /r/SaddestBackflip now turns into a website since people keep having to find different versions of the list

Probably easiest to create a static site based on Hugo, this theme seems to fit well: https://github.com/spaghettiwews/hugonews minimalistic HN-type of theme

People should be able to create a pull request for additions to the list, or create an issue so someone else can do it

Will probably add some maintainers since I don't want to be the arbiter of what constitutes a worthy addition

# Contributing

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

For older additions you will need to change the date

Add the itemurl's you know

- itemurl: the link to the article
- itemurl_archive: an archived link for if the original is removed
- itemurl_soccer: the link to the /r/soccer thread
- itemurl_saddestbackflip: the link to the /r/saddestbackflip thread

## Creating a pull request

TODO
