## akash provider lease-logs

get service status

```
akash provider lease-logs [flags]
```

### Options

```
      --dseq uint                deployment sequence
  -f, --follow                   Specify if the logs should be streamed. Defaults to false
      --format string            Output format text|json. Defaults to text (default "text")
      --from string              name or address of private key with which to sign
      --gseq uint32              group sequence (default 1)
  -h, --help                     help for lease-logs
      --home string              the application home directory
      --keyring-backend string   select keyring's backend (os|file|kwallet|pass|test) (default "os")
      --oseq uint32              order sequence (default 1)
      --provider string          provider
      --service string           name of service to query
  -t, --tail int                 The number of lines from the end of the logs to show. Defaults to -1 (default -1)
```

### Options inherited from parent commands

```
      --node string   The node address (default "http://localhost:26657")
```

### SEE ALSO

* [akash provider](akash_provider.md)	 - Akash provider commands

###### Auto generated by spf13/cobra on 18-Feb-2021
