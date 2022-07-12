## Links to tests 
This file collects links to integration tests for quick start. 

## PIX Query 
Used to interchange the local patient id with the global patient id used in the community incl. additional id's, i.e. the EPR-SPID: 

https://github.com/project-husky/husky/blob/master/husky-communication/husky-communication-gen/src/test/java/org/husky/communication/integration/PixV3QueryTest.java

## Registry Stored Query 
Used to find Document Metadata which include the data required to retrieve a document: 

https://github.com/project-husky/husky/blob/master/husky-communication/husky-communication-gen/src/test/java/org/husky/communication/integration/ConvenienceCommunicationQueryDocumentsTest.java

## Retrieve Documents
Used to retrieve a document (as binary) from a repository:

https://github.com/project-husky/husky/blob/master/husky-communication/husky-communication-gen/src/test/java/org/husky/communication/integration/ConvenienceCommunicationRetrieveDocumentsTest.java

## Provide and Register Documents
Used to store a set of documents to a repository and register the document metadata: 

https://github.com/project-husky/husky/blob/master/husky-communication/husky-communication-gen/src/test/java/org/husky/communication/integration/ConvenienceCommunicationSubmitDocumentTest.java

## ATNA Logging

ATNA Logs should be written automatically when calling the transaction. A test for this is:

https://github.com/project-husky/husky/blob/master/husky-communication/husky-communication-gen/src/test/java/org/husky/communication/integration/ConvenienceMasterPatientIndexV3AtnaAuditTest.java

## Get X-User Assertion
XUA (short for X User Assertion) defines to transactions. While the first is just adding the Assertion to the SOAP security header, 
the second is a transaction to exchange the Identity Assertion retrieved from the IdP to the X-User Assertion required for authorization.
A test for the latter may be found here: 

https://github.com/project-husky/husky/blob/master/husky-communication/husky-xua/husky-xua-ch-impl/src/test/java/org/husky/xua/communication/xua/impl/ch/integration/XuaClientTest.java




