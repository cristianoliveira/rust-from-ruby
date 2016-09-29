# rust-from-ruby
The repository of my presentation on The Developers Conference - POA - 2016

https://rust-from-ruby.herokuapp.com

# Simple Rust Web App
How it work?

It was made using Iron that is a high level web framework
built in and for Rust, built on hyper.

## Backend
- [iron](https://github.com/iron/iron)
- [staticfile](https://github.com/iron/staticfile)
- [monting](https://github.com/iron/mount)

## Frontend
The presentation was made using reveal.js

## Running
```bash
cargo run
```
And the server will be running at: `http://localhost:3000`

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

# LICENSE
MIT
