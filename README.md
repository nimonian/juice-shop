# ![Juice Shop Logo](https://raw.githubusercontent.com/juice-shop/juice-shop/master/frontend/src/assets/public/images/JuiceShop_Logo_100px.png) OWASP Juice Shop

> [The most trustworthy online shop out there.](https://twitter.com/dschadow/status/706781693504589824)
> ([@dschadow](https://github.com/dschadow))

OWASP Juice Shop is probably the most modern and sophisticated insecure web
application! It can be used in security trainings, awareness demos, CTFs and as
a guinea pig for security tools! Juice Shop encompasses vulnerabilities from the
entire [OWASP Top Ten](https://owasp.org/www-project-top-ten) along with many
other security flaws found in real-world applications!

![Juice Shop Screenshot Slideshow](screenshots/slideshow.gif)

## Guide

There is a
[companion guide](https://pwning.owasp-juice.shop/companion-guide/latest/index.html)
for this project. It's very useful and you should keep it open when working on
Juice Shop.

## Setup

### Running from source

Clone the repo locally or open in a Codespace and run:

1. `npm install`

2. `npm start`

### Docker

Install [Docker](https://www.docker.com) locally or open in a Codespace and run

1. Run `docker pull bkimminich/juice-shop`

2. Run `docker run --rm -p 127.0.0.1:3000:3000 bkimminich/juice-shop`

## Getting started

1. Read the
   [intro](https://pwning.owasp-juice.shop/companion-guide/latest/introduction/motivation.html)

2. Check out the
   [architecture](https://pwning.owasp-juice.shop/companion-guide/latest/introduction/architecture.html)

3. Read the
   [browser section](https://pwning.owasp-juice.shop/companion-guide/latest/part1/rules.html#_browser)
   of the recommended tools

4. Read about
   [finding the score-board](https://pwning.owasp-juice.shop/companion-guide/latest/part2/score-board.html)

> [!TIP]
>
> Once you find the scoreboard, it's a good idea to filter the challenges to
> show only those which have tutorials, and then approach them from easiest to
> hardest.

Happy hacking!
