# Google Cloud Functions

Google Cloud Functions is the easiest option to run code serverless in GCP, as it does not require any server or even container.
The runtime is completely provided by Google, you bring the code and Google does the rest.

Google offers a functions framework for a variety of languages:

- Node.js
- Go
- Java
- Python
- PHP
- Ruby
- .Net

It enables processing of HTTP requests and various cloud events, but the capabilities differ with generation 1 and 2 of the cloud functions.
Generation 2 can be used together with [EventArc](https://cloud.google.com/eventarc/docs/overview) to create an event driven architecture,
which means you have access to almost all possible events in Google cloud.



