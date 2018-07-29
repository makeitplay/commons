# MakeItPlay - Football Commons


[![GoDoc](https://godoc.org/github.com/makeitplay/commons?status.svg)](https://godoc.org/github.com/makeitplay/commons)
[![Go Report Card](https://goreportcard.com/badge/github.com/makeitplay/commons)](https://goreportcard.com/report/github.com/makeitplay/commons)

MakeItPlay - Football Commons is a [Go](http://golang.org/) library the provides some shareable features between the
game server and the clients of the MakeItPlay Football game. This lib is meant to be used by the  [Client Player](https://github.com/makeitplay/client-player-go)
implemented in Go. However, you may implement another client and use this lib as well.

If you wish to use part of this lib for any other project, please lt me know if you find bugs, I will fix as soon as possible.   


Notes:

1. Most part of this library code is not tested at the current version (1.0.0-alpha). And there is no plans to 
   improve its tests. I would appreciate it you could help with it, and I would be happy to include your name in the contributors list.
2. This lib uses MakeItPlay Football version 1.0.*-alpha constant values (distance, time, speed). Please, read the game documentation 
at the [Official website](http://www.makeitplay.ai) to further information about all units. 