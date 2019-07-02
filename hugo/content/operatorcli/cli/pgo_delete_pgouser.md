---
title: "pgo_delete_pgouser"
---
## pgo delete pgouser

Delete a pgouser

### Synopsis

Delete a pgouser. For example:

    pgo delete pgouser someuser

```
pgo delete pgouser [flags]
```

### Options

```
      --all         Delete all PostgreSQL Operator users.
  -h, --help        help for pgouser
      --no-prompt   No command line confirmation before delete.
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
      --disable-tls              Disable TLS authentication to the Postgres Operator.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo delete](/operatorcli/cli/pgo_delete/)	 - Delete an Operator resource

###### Auto generated by spf13/cobra on 15-Dec-2019