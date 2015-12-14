CLibpq
======

[![Swift 2.2](https://img.shields.io/badge/Swift-2.2-orange.svg?style=flat)](https://swift.org)
[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://swift.org)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](http://slack.zewo.io/badge.svg)](http://slack.zewo.io)

**CLibpq** provides PostgreSQL for **Swift 2.2**.

## Installation

- Install [`libpq`](http://www.postgresql.org/docs/9.1/static/libpq.html)

```bash
$ apt-get install libpq-dev
```

- Add `CLibpq` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Zewo/CLibpq.git", majorVersion: 0, minor: 1)
	]
)

```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](https://zewo-slackin.herokuapp.com)

Join us on [Slack](https://zewo-slackin.herokuapp.com).

License
-------

**CLibpq** is released under the MIT license. See LICENSE for details.
