# Swagger Accuracy Report
## What is this report about
[@Jeffrey to add details]

## How to improve report
There're two parts of the report need to be improved if it has content. 
* First part is `Failed Operations` which includes the schema validation errors for listed operations, all the errors are supposed to be fixed. From the error code you could browse to the linked document about the error defintion and fix tips.
* Second part is `Untested Operations` which includes the operations which don't have the traffic generated by RESTler for validation. It could be because the dependent operations fails in validation in which case please fix failed operation firstly so that this untested operation will be unlocked automatically.

## How to improve Untested Operations
All the traffics for each operation are generated by RESTler automatically, if the result says the operation is untested then you could try to modify RESTler config files to improve RESTler generation coverage.
[@Marina to add details on how to modify configs]

* Download and modify each RESTler config
[to add details]

* Debug locally with updated RESTler configs
[to add details]

* Check in updated RESTler configs to be used in swagger PR pipeline and re-run
[to add details]
