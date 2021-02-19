## cybr conjur logon

Logon to Conjur

### Synopsis

Authenticate to Conjur using API Key or password
	
	Example Usage:
	$ cybr conjur logon -a account -b https://conjur.example.com -l admin

```
cybr conjur logon [flags]
```

### Options

```
  -a, --account string    Conjur account
  -b, --base-url string   Conjur appliance URL
  -h, --help              help for logon
  -l, --login string      Conjur login name
      --self-signed       Retrieve and use self-signed certificate when sending requests to the Conjur API
```

### Options inherited from parent commands

```
      --verbose   To enable verbose logging
```

### SEE ALSO

* [cybr conjur](cybr_conjur.md)	 - Conjur actions

###### Auto generated by spf13/cobra on 19-Feb-2021