## The Project

The husky project (a synonym for heath usablity key) is intended to be
the key to unlock the door to the world of IHE XDS.b Affinity Domains, which
are the foundation of many infrastructures to exchange helathcare information
(like the Swiss EPR and ELGA in Austria).  

The intention is to enable developer and vendors to quickly implement the
required [IHE Profiles](https://profiles.ihe.net) to connect to the exchange
infrastructures freeing them to implement all the details of the interfaces
and messages. Although it is recommended to study the underlying specifications,
the intention of husky project is to provide a low barrier access which requires
only basic knowlegde of actors and transactions of the underlying IHE profiles.


## How to use

The husky project provides a software library written in the Java programming
language. It provides a thin layer on top of the more generic IPF framework,
which contributes the core implementation of the IHE transactions.

To use the husky library with your application to options are at hand:

- You may integrate the husky library as module in your application and use
the Java API to connect to the health exchange infrastructure.

- You may use the husky library to implement an adapter to convert your
favorite API technology to the IHE profiles required by the health exchange
infrastructure.

Each of the above variants have their advantages but also pitfalls and you may
choose based on your own requirements and preferred technologies.

Both of the above intergration methods are currently in use by contributer.
You'll find links to their experience reports below.       


## Behind the curtain

The development of the project is driven by the contributers, who actively use
the husky projects in real life projects.

The project is under the umbrella of two organizations which are actively driving
the standardization in the healthcare industry:

[IHE Suisse](https://www.ihe-suisse.ch/) is the national section of IHE
International in Switzerland and actively promoting the use of the profiles of
IHE International in the Swiss healthcare market.

[eHealth Suisse](https://www.e-health-suisse.ch/) is the swiss competence and
coordination centre of the Swiss confederation and the cantons.
