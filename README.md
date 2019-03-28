<img src="https://gophersource.com/img/go-balloons.png" width="150px"
align="right" />

# GopherSource: Go

This is a fork of the [upstream Go repository][go-git] as part of the
[GopherSource][gs] project where the community can try out changes to the 
`go` commands, a.k.a. the "toolchain", and provide feedback.

Tools and patches are built in an integration branch and binaries 
are made available for adventurous gophers to install on their
developer machines and CI servers. As we get a feel for what works
for us as a community, we then use the results of our experiences
to write solid experience reports and proposals upstream.

## Install From Source
You need to have [a working Go development environment][setup] before you can
build Go from source. The script below will compile Go and install it. The `go`
binary is placed in the bin directory and doesn't overwrite your existing go
installation.

### Bash
```
$ cd src
$ ./make.bash
$ export PATH="$PATH:$(go env GOPATH)/src/github.com/gophersource/go/bin"
```

### PowerShell
```
> cd src
> .\make.bat
> $env:PATH += ";$(go env GOPATH)\src\github.com\gophersource\go\bin"
```

### Contributing

We are actively seeking new contributors and ideas at all times! See our
[Contributing Guide][contributing] for how to get started.

We want to let you know that we follow a general [philosophy][philosophy] in how
we work together, and we'd really appreciate you getting familiar with it before
you start.

[gs]: https://gophersource.com
[go-git]: https://github.com/golang/go
[setup]: https://gophersource.com/setup
[contributing]: ./CONTRIBUTING.md
[philosophy]: https://gophersource.com/philosophy/