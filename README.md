# personal

Powered by Cloudflare Workers :)

here's what it does:

1. if you visit <https://ruin.cc/>, then you will be redirected to my Github.
2. I can quickly add my ssh pub keys to the server I want to login by using `curl https://ruin.cc/keys.sh | sh`.

TODO:

- [ ] push message to myself (wechat|qq|ding|telegram)

## usage

### keys

<https://ruin.cc/keys>

### set authorized_keys

```shell
curl https://ruin.cc/keys.sh | sh
```

## dev

```shell
yarn install
yarn wrangler login
yarn dev
```

### publish

publish:

```shell
yarn wrangler login
yarn run publish
```
