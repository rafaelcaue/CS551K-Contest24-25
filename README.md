CS551K 2024-2025 - Assessment 3 - Multi-Agent Programming Contest
============================

This assessment is based on the 
[Multi-Agent Programming Contest](https://multiagentcontest.org/),
where participants program agents to compete with each other in a
predefined game.

_MASSim_ simulations run in discrete steps. Agents connect remotely to the
contest server, receive percepts and send their actions, which are in turn
executed by _MASSim_.

<p align="center">
  <img src="https://multiagentcontest.org/2019/banner.png">
</p>

Download
--------

Clone this repository (or download it as zip).

Documentation
-------------

[server.md](docs/server.md) describes how the _MASSim_ server can be configured and started.

[scenario.md](docs/scenario.md) contains the description of the current scenario.

[protocol.md](docs/protocol.md) describes the _MASSim_ protocol, i.e. message formats for communicating with the _MASSim_ server.

[eismassim.md](docs/eismassim.md) explains _EISMASSim_, a Java library using the Environment Interface Standard (EIS) to communicate with the _MASSim_ server, that can be used with platforms which support the EIS.

[monitor.md](docs/monitor.md) describes how to view live matches and replays in the browser.

License
-------

_MASSim_ is licensed under the AGPLv3+. See COPYING.txt for the full
license text.
