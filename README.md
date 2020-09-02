# FeelsTheme (Member)

A custom, responsive and modern theme for https://member.cash created by @Feels using SCSS

## Member

Member is a Bitcoin Cash blockchain browser. It reads and allows users to create actions in the Memo/Member protocol.
Notably it displays and creates posts, likes, tips, profiles, reputational ratings and geolocated posts.
It is designed to be a 'fat' javascript client app that runs against a relatively dumb server.
You can see it online here - https://member.cash

## Getting Started

Before making changes, it would be a good idea to check
out [the contribution guidelines](CONTRIBUTING.md)
and [open issues](https://github.com/memberapp/memberapp.github.io/issues)

To get started locally clone the following repo https://github.com/FreeTrade/memberdev

Serve the directory as a web-page via node

    npm install reload -g
    npx reload

When using `localhost:*` Most modern browsers will enable the service worker
and dynamically loaded scripts.

Clone this repo.

Open a new termianl and run the following command

    npx gulp watch

Edit the base theme by navigating to `/src/feels`

The final css file will be imported to `/memberdev/css`
