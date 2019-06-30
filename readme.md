# AWS DynamoDB with Axios [![CircleCI](https://circleci.com/gh/possibilities/aws-dynamodb-axios.svg?style=svg)](https://circleci.com/gh/possibilities/aws-dynamodb-axios)

A small replacement for AWS [DynamoDb DocumentClient](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/DynamoDB/DocumentClient.html) and [DynamoDB Converter](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/DynamoDB/Converter.html) based on the [Axios request library](https://github.com/axios/axios) and [AWS4](https://github.com/mhart/aws4).

## Usage

For now see [test suite](./__tests__) for usage

## API

### Client

#### Configure

###### `dynamodb()`

##### Operations

###### `get()`

###### `put()`

###### `update()`

###### `delete()`

###### `query()`

###### `scan()`

###### `batchGet()`

###### `batchWrite()`

###### `transactGet()`

###### `transactWrite()`

###### `createTable()`

###### `describeTable()`

#### Conversion

###### `marshall(obj|arr)`

###### `unmarshall(obj|arr)`
