---
title: Introduction
description: Easy implementation of the JSON-RPC 2.0 server for the Laravel framework.
extends: _layouts.documentation
section: content
---

# Welcome

## Introduction

**Sajya** is an open and free project whose goal is to provide easy implementation of the JSON-RPC 2.0 server for the Laravel framework.

The manual contains information on using the package but does not explain the use of the framework. 
It is strongly recommended that you read the [Laravel documentation](https://laravel.com/docs/).


----


## What is JSON-RPC 2.0?

It is a simple stateless protocol for creating Remote Procedure Call (RPC) style APIs.

For example, you have an endpoint on the server that accepts requests and response with a body like:

```json
{"jsonrpc": "2.0", "method": "subtract", "params": {"minuend": 42, "subtrahend": 23}, "id": 3}
{"jsonrpc": "2.0", "result": 19, "id": 3}
```

An example of an error:

```json
{"jsonrpc": "2.0", "error": {"code": 1234, "message": "Description of error"}, "id": "1"}
```

You can find out more on the [specification page](/docs/specification).


## How to install?

The package is freely distributed over the Internet, [source codes](https://github.com/sajya/server), and [release notes](https://github.com/sajya/server/releases) are published on GitHub.
The [installation manual](/docs/installation/) contains detailed instructions.


> To suggest improvements to this guide, [create a new issue](https://github.com/sajya/sajya.github.io/issues/new).
If you have questions or find an error in the documentation, please indicate the chapter and accompanying text to indicate an error.
