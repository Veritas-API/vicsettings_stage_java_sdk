# VeritasInformationClassifierVICApi

All URIs are relative to *http://veritas-nonprod-stage.apigee.net/vic/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getSettings**](VeritasInformationClassifierVICApi.md#getSettings) | **GET** /settings | Get settings


<a name="getSettings"></a>
# **getSettings**
> Settings getSettings()

Get settings



### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.VeritasInformationClassifierVICApi;


VeritasInformationClassifierVICApi apiInstance = new VeritasInformationClassifierVICApi();
try {
    Settings result = apiInstance.getSettings();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling VeritasInformationClassifierVICApi#getSettings");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Settings**](Settings.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

