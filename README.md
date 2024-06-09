# GORM SQL Server Driver

## USAGE

```go
import (
  "github.com/wubin1989/sqlserver"
  "github.com/wubin1989/gorm"
)

// github.com/microsoft/go-mssqldb
dsn := "sqlserver://gorm:LoremIpsum86@localhost:9930?database=gorm"
db, err := gorm.Open(sqlserver.Open(dsn), &gorm.Config{})
```

Checkout [https://github.com/wubin1989](https://github.com/wubin1989) for details.
