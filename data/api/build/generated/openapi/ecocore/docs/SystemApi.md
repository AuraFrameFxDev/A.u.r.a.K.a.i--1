# SystemApi

All URIs are relative to *https://api.auraframefx.com/v2*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**healthCheck**](SystemApi.md#healthCheck) | **GET** /health | Health check endpoint |


<a id="healthCheck"></a>
# **healthCheck**
> HealthResponse healthCheck()

Health check endpoint

Returns API health status

### Example
```kotlin
// Import classes:
//import org.openapitools.client.infrastructure.*
//import dev.aurakai.auraframefx.model.ecocore.*

val apiInstance = SystemApi()
try {
    val result : HealthResponse = apiInstance.healthCheck()
    println(result)
} catch (e: ClientException) {
    println("4xx response calling SystemApi#healthCheck")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling SystemApi#healthCheck")
    e.printStackTrace()
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**HealthResponse**](HealthResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

