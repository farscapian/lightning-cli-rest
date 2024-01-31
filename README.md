# lightning-cli-rest

An interactive "lightning-cli" that allows you to interact with a CLN REST endpoint. You MUST use the `-k` (parameter) and provide key=value pairs for ALL commands requiring parameters. example:

```
./lighting-cli invoice -k amount_msat=100000 description="test" label="test1"
```