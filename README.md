# slack-keep-presence

Keeps your slack user active whenever auto-away kicks in.

## Installation

```
$ npm install slack-keep-presence
```

## Usage

```
$ slack-keep-presence -t <your token>
```
```
$ SLACK_TOKEN=<your_token> slack-keep-presence
```

You can get a token linked to your user at https://api.slack.com/web

## Motivation

https://twitter.com/slackhq/status/448966862521786368
> Disabling auto-away isn't on our immediate roadmap, but it's on our "someday"
list. Stay tuned! ✨

Auto-away in slack is annoying. Not lurking around slack for 30 minutes does not
mean not being available for anyone to ping and "someday" seems a bit vague for
an essential feature like this. Fortunately using the slack API it's easy to
circumvent this restriction.
