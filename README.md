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

## atomun-mnemonic

The [atomun-mnemonic](https://github.com/harningt/atomun-mnemonic) project implements the necessary
details to generate mnemonic sequences and turn them into data that can be used to generate
Bitcoin keys. The mechanism can also be used in other ways, such as encrypting data.

[![Build Status](https://travis-ci.org/harningt/atomun-mnemonic.svg?branch=develop)](https://travis-ci.org/harningt/atomun-mnemonic)

[Apache2.0]: http://www.apache.org/licenses/LICENSE-2.0
[SemVer2.0]: http://semver.org/spec/v2.0.0.html
