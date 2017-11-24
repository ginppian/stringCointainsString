String Contains Another String
========

## Description

For *Swift 3* with Foundation Framework

## Code

```Swift
var string = "hello Swift"

if string.range(of:"Swift") != nil { 
    print("exists")
}

// alternative: not case sensitive
if string.lowercased().range(of:"swift") != nil {
    print("exists")
}
```

## Fuente

* <a href="https://stackoverflow.com/questions/24034043/how-do-i-check-if-a-string-contains-another-string-in-swift">Stack Over Flow</a>