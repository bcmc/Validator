## STIX Validator for FLAREclient 2.0.4 and FLAREgateway Validation Service

### To create the .jar
1) Clone the repository, navigate to the directory
2) Execute the following:
`jar cvf STIX_Validator.jar \*`

### To update schemas:
All of the schemas have offline, relative path references to their schema locations. If you add schemas, you must ensure the schema locations include relative references to their dependencies.
