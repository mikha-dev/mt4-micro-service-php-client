# Swagger\Client\InitApi

All URIs are relative to *https://apps.noorcm.com:6502/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**initGet**](InitApi.md#initGet) | **GET** /init | Init manager


# **initGet**
> initGet($server, $login, $password, $accept)

Init manager

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\InitApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$server = "server_example"; // string | 
$login = "login_example"; // string | 
$password = "password_example"; // string | 
$accept = "accept_example"; // string | 

try {
    $apiInstance->initGet($server, $login, $password, $accept);
} catch (Exception $e) {
    echo 'Exception when calling InitApi->initGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **server** | **string**|  |
 **login** | **string**|  |
 **password** | **string**|  |
 **accept** | **string**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

