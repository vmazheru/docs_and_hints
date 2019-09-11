# Apache Nifi Notes

## The Four V's of Big Data

 - **Volume** (how much data generated)
 - **Velocity** (the speed of transferring of data)
 - **Variety** (refers to different types of data)
 - **Veracity** (refers to the messines or trustworthiness of the data)


## Flow Based Programming (FBP)

Flow Based Programming is a programming paradigm that defines applications as networks of "black box" processes,
which exchange data across predefined connections by message passing,
where the connections are specified externally to the processes.

These black box processes can be reconnected endlessly to form different applications without having to be changed internally.
FBP is thus naturally component-oriented.


## Types of Processors

 - Data Ingestion Processors
 	- GenerateFlowFiles
 	- GetFile
 	- GetFTP
 	- GetSFTP
 	- GetJMSQueue
 	- GetJMSTopic
 	- GetHTTP
 	- ListenHTTP
 	- ListenUDP
 	- GetHDFS
 	- GetKafka
 	- QueryDatabaseTable
 	- GetMongo
 	- GetTwitter
 	- ListHDFS/FetchHDFS
 - Data Transformation Processors
 	- ConvertRecord
 	- UpdateRecord
 	- ConvertJSONToSQL
 	- ReplaceText
 	- CompressContent
 	- ConvertCharacterSet
 	- EncryptContent
 	- TransformXML
 	- JoltTranformJSON
 - Data Egress / Sending Data Processors
 	- PutEmail
 	- PutFile
 	- PutFTP
 	- PutSFTP
 	- PutJSM
 	- PutSQL
 	- PutKafka
 	- PutMongo
 	- PutHDFS
 - Routing and Mediation Processors
 	- ControlRate
 	- DetectDuplicate
 	- DistributeLoad
 	- RouteOnAttribute
 	- RouteOnContent
 	- ScanAttribute
 	- ScanContent
 	- ValidateXml
 	- ValidateCSV
 - Database Access Processors
 	- ConvertJSONToSQL
 	- ExecuteSQL
 	- PutSQL
 	- SelectHiveQL
 	- PutHiveQL
 	- ListDatabaseTables
 - Attribute Extraction Processors
 	- EvaluateJsonPath
 	- EvaluateXPath
 	- EvaluateXQuery
 	- ExtractText
 	- HashAttribute
 	- HashContent
 	- IdentityMimieType
 	- UpdateAttribute
 	- LogAttribute
 - System Interaction Processors
 	- ExecuteProcess
 	- ExecuteStreamCommand
 - Splitting and Aggregation Processors
 	- SplitText
 	- SplitJson
 	- SplitXml
 	- SplitRecord
 	- SplitContent
 	- UnpackContent
 	- SegmentContent
 	- MergeContent
 	- QueryRecord
 - HTTP and UDP Processors
 	- GetHTTP
 	- ListenHTTP
 	- InvokeHTTP
 	- PostHTTP
 	- HandleHttpRequest
 	- HandleHttpResponse
 	- ListenUDP
 	- PutUDP
 	- ListenUDPRecord
 - AWS Processors
 	- FetchS3Object
 	- PutS3Object
 	- PutSNS
 	- GetSQS
 	- PutSQS
 	- DeleteSQS
 	- GetDynamoDB
 	- PutDynamoDB
 	- PutLambda
