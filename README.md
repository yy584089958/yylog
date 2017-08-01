##go log 学习
```go
package main

import "yylog"

func main(){
    var log *yylog.Log = yylog.New(yylog.Debug,"log.log")
    log.Debug("debug")
    log.Info("123")
    log.Warning("aaa")
}
```
