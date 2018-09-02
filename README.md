# Plume
Plume is a MapReduce framework written in C++.
_Powerful, useful and cloud-service provider agnostic._

- [Features](#features)
- [Component Libraries](#component-libraries)
- [Requirements](#requirements)
- [Installation](#installation)
- [FAQ](#faq)
- [Credits](#credits)
- [License](#license)

## Features

- [ ] Map & reduce tasks
- [ ] Support Google Cloud, Amazon Web Services and Microsoft Azure as resource provider
- [ ] Read input from text file, MySQL and PostgreSQL
- [ ] Store output to cloud service
- [ ] Comprehensive Unit and Integration Test Coverage
- [ ] Complete Documentation

## Component Libraries

Plume combines a collection of C++ libraries into a single MapReduce framework. In order to keep it clean, easy to extend and maintain, and powerful, it is splitted some component libraries.

- [Pwing](#) - Provides an abstraction and a few implementations for requesting and managing machine resources from cloud providers.
- [Pexec](#) - Generates and optimizes an execution graph from user-defined MapReduces tasks.
- [Panager](#) - Orchestrates execution and resource usage.
- [PUI](#) - Web interface with realtime execution updates.

## Requirements

- C++ 14

## Installation

Coming soon.

## FAQ

### What's the origin of the name Plume?

Plume is lightweight, useful to fly and close enough to Flume.

### What's Flume?

Plume is heavily based on FlumeJava, a Java library for MapReduce tasks by Google. You can find more information in [this paper](https://ai.google/research/pubs/pub35650).

## Credits

Plume is owned and maintained by [YAIO](https://github.com/yetanotherio), an engineering organization focused on building systems for fun.

## License

Plume is released under the GNU GPL v3 license. [See LICENSE](https://github.com/yetanotherio/plume/blob/master/LICENSE) for details.
