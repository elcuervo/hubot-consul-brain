# Hubot Consul Brain

This hubot script allows Hubot to store the bot information in Consul KV store.

## Install
```bash
npm install hubot-consul-brain
```

## Usage
Then add `hubot-consul-brain` to the list of `external-scripts.json`.

The script expects `CONSUL_HOST` and `CONSUL_PORT` or it will just use default
values: `127.0.0.1` and `8500`.

Additionally  you can also pass in `CONSUL_TOKEN` if your consul instance uses
ACLs.
