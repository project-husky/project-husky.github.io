## The Project

The husky project (a synonym for heath usablity key) is intended to be
the key to unlock the door to IHE XDS.b Affinity Domains, which
are the foundation of many infrastructures to exchange healthcare information
(like the Swiss EPR and ELGA in Austria).  

The intention is to enable developer and vendors to quickly implement the
required [IHE Profiles](https://profiles.ihe.net) to connect to the exchange
infrastructures freeing them to implement all the details of the interfaces
and messages.

Although it is strongly recommended to study the underlying profiles and
specifications, the intention of husky project is to provide a low barrier
access which requires only basic knowlegde of actors and transactions of
the underlying IHE profiles.


## How to use

The husky project provides a software library written in the Java programming
language. It provides a thin layer on top of the more generic
[IPF framework](http://oehf.github.io/ipf/ipf-platform-camel-ihe/index.html),
which contributes the core implementation of the IHE transactions.

To use the husky library with your application to options are at hand:

- You may integrate the husky library as module in your application and use
the Java API to connect to the health exchange infrastructure.

- You may use the husky library to implement an adapter to convert your
favorite API technology to the IHE profiles required by the health exchange
infrastructure.

Each of the above variants have their advantages but also pitfalls and you may
choose based on your own requirements and preferred technologies. Both of the
above integration methods are currently in use by contributers. You'll find links
to their experience reports below.

If we draw your interest, please check out the husky
[getting started guide](./getting_started.md).      


## Behind the curtain

The development of the project is driven by the contributers, who actively use
the husky projects in real life projects.

The project is actively maintained by
[eHealth Suisse](https://www.e-health-suisse.ch/), the swiss competence and
coordination centre of the Swiss confederation and the cantons and maintains
the national profiles for healthcare interoperability.

The project is hosted under the umbrella of [IHE Suisse](https://www.ihe-suisse.ch/)
is the national section of IHE International in Switzerland and actively promoting
the use of the profiles of IHE International in the Swiss healthcare market.
