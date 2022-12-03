# go-diskqueue

[![Build Status](https://github.com/iseletsk/go-diskqueue/workflows/tests/badge.svg)](https://github.com/iseletsk/go-diskqueue/actions) [![Go Reference](https://pkg.go.dev/badge/github.com/iseletsk/go-diskqueue.svg)](https://pkg.go.dev/github.com/iseletsk/go-diskqueue) [![GitHub release](https://img.shields.io/github/release/iseletsk/go-diskqueue.svg)](https://github.com/iseletsk/go-diskqueue/releases/latest)

A Go package providing a filesystem-backed FIFO queue

Pulled out of https://github.com/nsqio/nsq

This fork implements adds MaxDepth parameter, and a method IsFull() to check if the queue depth reached MaxDepth.
