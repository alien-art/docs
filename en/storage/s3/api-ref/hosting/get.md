# get method

Returns the configuration of static website hosting for a bucket.


## Request {#request}

```http
GET /{bucket}?website HTTP/2
```

### Path parameters {#path-parameters}

Parameter | Description
----- | -----
`bucket` | Bucket name.


### Query parameters {#request-params}

Parameter | Description
----- | -----
`website` | Required parameter that indicates the type of operation.


### Headers {#request-headers}

Use the appropriate [common headers](../common-request-headers.md) in your request.


## Response {#response}

### Headers {#response-headers}

Responses can only contain [common response headers](../common-response-headers.md).

### Response codes {#response-codes}

For a list of possible responses, see [{#T}](../response-codes.md).

### Data schema {#response-scheme}

The structure of returned data is the same as the structure of the data passed by the [upload](upload.md) method.

{% include [the-s3-api-see-also-include](../../../../_includes/storage/the-s3-api-see-also-include.md) %}