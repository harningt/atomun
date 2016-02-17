# Atomun
Enter Atomun - the Java Bitcoin utility library collection.

# Communications
The project hosts a live chatroom through Gitter, currently as an experiment.

[![Join the chat at https://gitter.im/harningt/atomun](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/harningt/atomun?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

As the project grows, further communication channels may be assigned / opened up.

# Sub-projects
The project is broken out into many distinct sub-projects. This offers the following benefits:
* Divide responsibility firmly
* Offer more re-usable components without forcing the kitchen sink
* Promote development progress by preventing decision paralysis from stopping _all_ progress by keeping multiple pieces open

All projects, unless otherwise noted, are under the [Apache 2.0 license][Apache2.0].

Also, all libraries will follow the guidelines set forth in [Semantic Versioning 2.0][SemVer2.0]

## atomun-core

The [atomun-core](https://github.com/harningt/atomun-core) project implements base necessary
utilities to be used (eventually) by the other projects.

This leaves the potential for the core project to implement test helper and this (atomun) project
to combine all of the projects into a nice UI for visual experimentation.

DEVELOP [![Build Status](https://travis-ci.org/harningt/atomun-core.svg?branch=develop)](https://travis-ci.org/harningt/atomun-core) [![codecov.io](https://codecov.io/github/harningt/atomun-core/coverage.svg?branch=develop)](https://codecov.io/github/harningt/atomun-core?branch=develop)
MASTER [![Build Status](https://travis-ci.org/harningt/atomun-core.svg?branch=master)](https://travis-ci.org/harningt/atomun-core) [![codecov.io](https://codecov.io/github/harningt/atomun-core/coverage.svg?branch=master)](https://codecov.io/github/harningt/atomun-core?branch=master)

## atomun-mnemonic

The [atomun-mnemonic](https://github.com/harningt/atomun-mnemonic) project implements the necessary
details to generate mnemonic sequences and turn them into data that can be used to generate
Bitcoin keys. The mechanism can also be used in other ways, such as encrypting data.

DEVELOP [![Build Status](https://travis-ci.org/harningt/atomun-mnemonic.svg?branch=develop)](https://travis-ci.org/harningt/atomun-mnemonic) [![codecov.io](https://codecov.io/github/harningt/atomun-mnemonic/coverage.svg?branch=develop)](https://codecov.io/github/harningt/atomun-mnemonic?branch=develop)
MASTER [![Build Status](https://travis-ci.org/harningt/atomun-mnemonic.svg?branch=master)](https://travis-ci.org/harningt/atomun-mnemonic) [![codecov.io](https://codecov.io/github/harningt/atomun-mnemonic/coverage.svg?branch=master)](https://codecov.io/github/harningt/atomun-mnemonic?branch=master)

## atomun-keygen

The [atomun-keygen](https://github.com/harningt/atomun-keygen) project implements the necessary
details to generate keys using deterministic / random key algorithms to implement useful
wallets.

DEVELOP [![Build Status](https://travis-ci.org/harningt/atomun-keygen.svg?branch=develop)](https://travis-ci.org/harningt/atomun-keygen) [![codecov.io](https://codecov.io/github/harningt/atomun-keygen/coverage.svg?branch=develop)](https://codecov.io/github/harningt/atomun-keygen?branch=develop)
MASTER [![Build Status](https://travis-ci.org/harningt/atomun-keygen.svg?branch=master)](https://travis-ci.org/harningt/atomun-keygen) [![codecov.io](https://codecov.io/github/harningt/atomun-keygen/coverage.svg?branch=master)](https://codecov.io/github/harningt/atomun-keygen?branch=master)

[Apache2.0]: http://www.apache.org/licenses/LICENSE-2.0
[SemVer2.0]: http://semver.org/spec/v2.0.0.html
