# Scribe 📜
Scribe is a very simple logging utility for Go applications.

## Installation
As with any Go package, scribe can be installed via `go get`:
```bash
go get github.com/bauenlabs/scribe
```

And then import in your application:
```go
import "github.com/bauenlabs/scribe"
```

## Usage

#### func  Error

```go
func Error(err error)
```
Error prints a error log.

#### func  Fatal

```go
func Fatal(err error, statusCode int)
```
Fatal prints a fatal error log.

#### func  Info

```go
func Info(logString string)
```
Info prints a info log.

#### func  Trace

```go
func Trace(logString string)
```
Trace prints a trace log.

#### func  Warning

```go
func Warning(logString string)
```
Warning prints a warning log.

# scribe
--
    import "github.com/bauenlabs/scribe"

Scribe provides a standard set of logging tools.

## Usage


scribe

github.com/bauenlabs/scribe
