# go-cmdlog

A simple and crude go package for datexla logger, just work in Linux and OSX

## Getting Started

``` go
package main

import (
    cmdlog "github.com/datexla/go-cmdlog"
)

func main() {
	cmdlog.Write(cmdlog.Debug, "Log Content", cmdlog.DefaultPathToFile)
}
```

## Installation

```
go get github.com/datexla/go-cmdlog
```
