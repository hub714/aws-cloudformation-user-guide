# Amazon S3 Bucket FilterRule<a name="aws-properties-s3-bucket-notificationconfiguration-config-filter-s3key-rules"></a>

`Rules` is a property of the [S3KeyFilter](aws-properties-s3-bucket-notificationconfiguration-config-filter-s3key.md) property that describes the Amazon Simple Storage Service \(Amazon S3\) object key name to filter on and whether to filter on the suffix or prefix of the key name\.

## Syntax<a name="w13ab1c21c10d204c13c62b5"></a>

### JSON<a name="aws-properties-s3-bucket-notificationconfiguration-config-filter-s3key-rules-syntax.json"></a>

```
{
  "[Name](#cfn-s3-bucket-notificationconfiguraiton-config-filter-s3key-rules-name)" : String,
  "[Value](#cfn-s3-bucket-notificationconfiguraiton-config-filter-s3key-rules-value)" : String
}
```

### YAML<a name="aws-properties-s3-bucket-notificationconfiguration-config-filter-s3key-rules-syntax.yaml"></a>

```
[Name](#cfn-s3-bucket-notificationconfiguraiton-config-filter-s3key-rules-name): String
[Value](#cfn-s3-bucket-notificationconfiguraiton-config-filter-s3key-rules-value): String
```

## Properties<a name="w13ab1c21c10d204c13c62b7"></a>

`Name`  <a name="cfn-s3-bucket-notificationconfiguraiton-config-filter-s3key-rules-name"></a>
Whether the filter matches the prefix or suffix of object key names\. For valid values, see the `Name` request element of the [PUT Bucket notification](https://docs.aws.amazon.com/AmazonS3/latest/API/RESTBucketPUTnotification.html) action in the *Amazon Simple Storage Service API Reference*\.  
*Required*: Yes  
*Type*: String

`Value`  <a name="cfn-s3-bucket-notificationconfiguraiton-config-filter-s3key-rules-value"></a>
The value that the filter searches for in object key names\.  
*Required*: Yes  
*Type*: String