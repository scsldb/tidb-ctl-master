## tidb-ctl base64decode

decode base64 value

### Synopsis

decode base64 value to hex and uint64

```
tidb-ctl base64decode [flags]
```

### Examples

```
tidb-ctl base64decode [base64_data]
tidb-ctl base64decode [db_name.table_name] [base64_data]
tidb-ctl base64decode [table_id] [base64_data]
```

### Options

```
  -h, --help   help for base64decode
```

### SEE ALSO

* [tidb-ctl](tidb-ctl.md)	 - TiDB Controller

###### Auto generated by spf13/cobra on 30-Mar-2020