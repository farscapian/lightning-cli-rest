# lightning-cli-rest

An interactive "lightning-cli" that allows you to interact with a CLN REST endpoint. You MUST use the `-k` (parameter) and provide key=value pairs for ALL commands requiring parameters. example:

```
./lighting-cli invoice -k amount_msat=100000 description="test" label="test1"
```

The first time you run the `lightning-cli` command, a `.env` MAY be stubbed out. This is where you put your CLN Rune and REST point information.