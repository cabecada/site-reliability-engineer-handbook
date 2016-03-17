# HBase Shell Commands in Practice

**HBase Shell Usage**
* Quote all names in HBase Shell such as table and column names.
* Commas delimit command parameters.
* Type <RETURN> after entering a command to run it.
* Dictionaries of configuration used in the creation and alteration of tables are Ruby Hashes.
They look like this:

```hbase
{‘key1′ => ‘value1′, ‘key2′ => ‘value2′, …}
```

and are opened and closed with curley-braces.