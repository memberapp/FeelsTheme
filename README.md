# FeelsTheme

## Member

Member is a Bitcoin Cash blockchain browser. It reads and allows users to create actions in the Memo/Member protocol.
Notably it displays and creates posts, likes, tips, profiles, reputational ratings and geolocated posts.
It is designed to be a 'fat' javascript client app that runs against a relatively dumb server.
You can see it online here - https://member.cash

## Getting Started

Before making changes, it would be a good idea to check
out [the contribution guidelines](CONTRIBUTING.md)
and [open issues](https://github.com/memberapp/memberapp.github.io/issues)

To get started locally, simply open `index.html` in Firefox or Chrome, that's it.

Alternatively, the client can also be hosted directly from github pages,
by going to **Settings > Github Pages** from a forked version

A more roust way is to serve the directory as a web-page via node or python:

    npm install reload -g
    reload

or

    python3 -m http.server -p 8080

When using `localhost:*` Most modern browsers will enable the service worker
and dynamically loaded scripts.

## Theme Dev

Developed using `SCSS`

Using Node in a new termainal run the following commands

    npm i
    npx reload

Navigate to the `localhost:*` address

Open a new termianl and run the following command

    npx gulp watch

Edit the base theme by navigating to `/src/feels`

## Client

The client is an HTML5/JS BCH blockchain browser app with no outside js
dependencies.

It connects to a Member server to get content and broadcast transactions. It
can also get utxos from a Member server if that server has a BCHD utxo index.
Otherwise it gets utxos from Bitbox
