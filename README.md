# Web3 Authenticator

## 💻 Build it

```shell
# 1. install
> yarn
# 2. run
> node index.js 
```

## 🍬 Run it with Caddy

> Make sure  you have IPFS run localhost

Config it in `Caddyfile`

```json
yourgateway.ipfs {
    reverse_proxy 127.0.0.1:5050
}
```

Then, you can access your IPFS gateway with substrate-based authentication service! 🤟🏻

## 🙋🏻‍♂️ Contribute

Feel free to contribute with a PR!

## License

MIT
