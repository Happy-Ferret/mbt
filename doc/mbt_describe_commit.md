## mbt describe commit

Describe all modules in the specified commit

### Synopsis


Describe all modules in the specified commit

Commit SHA must be the complete 40 character SHA1 string.

If --content flag is specified, this command will describe just the modules
impacted by the specified commit.


```
mbt describe commit <sha> [flags]
```

### Options

```
  -c, --content       Describe the modules impacted by the changes in commit
  -f, --fuzzy         Use fuzzy match when filtering
  -h, --help          help for commit
  -n, --name string   Describe modules with a name that matches this value. Multiple names can be specified as a comma separated string.
```

### Options inherited from parent commands

```
      --debug       Enable debugging
      --graph       Format output as dot graph
      --in string   Path to repo
      --json        Format output as json
```

### SEE ALSO
* [mbt describe](mbt_describe.md)	 - Describe the modules in the repo

###### Auto generated by spf13/cobra on 20-Apr-2018
