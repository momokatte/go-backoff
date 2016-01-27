
# go-backoff

A Go library for backoff functions.

It provides implementation of the following algorithms:
- Power-of-2 exponential backoff
- Exponential backoff with half jitter
- Exponential backoff with full jitter

Backoff is an important part of rate limiting. This AWS blog post demonstrates the benefits of adding jitter to backoff behavior: https://www.awsarchitectureblog.com/2015/03/backoff.html


## Online GoDoc

https://godoc.org/github.com/momokatte/go-backoff
