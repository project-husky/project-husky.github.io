## Getting started

### Installation Guide

First of all please check out the husky
[installation guide](https://github.com/project-husky/husky/blob/master/docs/Installation.md).

In the installation guide you'll find the requirements to use the husky project
in your environment and the steps required to install the runtime.  


### Best to start

You'll find the list of profiles currently supported by the project in the
[README](https://github.com/project-husky/husky#implemented-ihe-profiles)
file of the project and some additional information, if you follow the links.

All supported profiles are accompanied by integration tests which show the
basic usage. The integration tests are performed against the
[EPR Reference environment](https://github.com/ehealthsuisse/EPD-by-example/blob/main/files/gazelle.md#epr-reference-environment). This may provide a good starting point. You find a list of links to the integrations tests for the basic transactions [here](./links_2_tests.md).

You may switch to the EPR Playground test environment by changing the endpoint
URL of the transactions. Please checkout the URL published by the
[EPR Playground](https://github.com/ehealthsuisse/EPD-by-example/blob/main/files/playground.md#epr-playground).

Please note, that both test environments implement the Swiss national extensions
of the underlying IHE Profiles, but the adpation to other national extensions
should be quite simple.    


### Additional information

You may find additional or accompanying information on one of the following pages:

- For the core profiles of IHE ITI, please checkout the
[IHE ITI Technical Framework](https://profiles.ihe.net/ITI/TF/index.html) page.

- Husky implements some profiles published as
[Supplements for Trial Implementation](https://profiles.ihe.net/ITI/#1.5).

- If you are looking for information on the application of the profiles for the
Swiss EPR, the [general information](https://www.e-health-suisse.ch/technik-semantik/epd-anbindung.html)
and the [commented examples](https://github.com/ehealthsuisse/EPD-by-example/blob/main/README.md#swiss-epr-transactions) might be of help for you.
