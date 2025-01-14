<h1 align="center">
  <img src="https://github.com/30440r/30440r.github.io/blob/master/img/cydia.png?raw=true"><br>
  canijailbreak
</h1>

<p align="center">
  <a href="http://30440r.xyz/canijailbreak"><img src="https://badgen.net/badge/Status/Updated/green" alt="Status"></a>
</p>
<p align="center">
A website which tells you whether you can jailbreak your iPhone, iPad, iPod touch or Apple TV.
</p>

## Contributing

We welcome contributions to the code/design/data of the site! Currently, it's fairly basic.

A few guidelines for contributing:

1. ~**No beta jailbreaks**~ - this rule seems more and more impossible to follow given the nature of most current jailbreaks. I ask that jailbreaks are at least reasonably stable before listed here - last thing Can I Jailbreak wishes to do is accidentally disable or break someone's device.
2. **No beta iOS versions**
3. **Use one pull request per jailbreak addition** - this will allow us to easily approve/reject new additions on a one-by-one basis.
4. Commit tags for new jailbreaks, in the form of `[jailbreak] <name> <version> for <iOS versions>` are recommended :)
5. Try to find the _simplest_ route to jailbreak, such as one click GUIs, that support _as many devices/iOS versions as possible_.


## installation

```bash

$ go get github.com/30440r/canijailbreak
$ cd $GOPATH/src/github.com/30440r/canijailbreak
$ go build .
```

## running it

```bash
$ ./canijailbreak --help
```

This will generate output, by default into `./static`. 

## adding jailbreaks

look in the file `./jailbreaks.yml` for a layout

then run the `./canijailbreak` util again
