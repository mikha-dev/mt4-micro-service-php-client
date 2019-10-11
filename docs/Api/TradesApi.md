# Swagger\Client\TradesApi

All URIs are relative to *https://apps.noorcm.com:6502/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**tradesByUserLoginGet**](TradesApi.md#tradesByUserLoginGet) | **GET** /trades/{user_login} | Get list of trade tickets
[**usersReportPost**](TradesApi.md#usersReportPost) | **POST** /users/report | Get list of user trades


# **tradesByUserLoginGet**
> tradesByUserLoginGet($token, $user_login)

Get list of trade tickets

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TradesApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$user_login = 56; // int | 

try {
    $apiInstance->tradesByUserLoginGet($token, $user_login);
} catch (Exception $e) {
    echo 'Exception when calling TradesApi->tradesByUserLoginGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **user_login** | **int**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **usersReportPost**
> usersReportPost($token, $r, $accept, $content_type, $body)

Get list of user trades

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TradesApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$r = 56; // int | 
$accept = "accept_example"; // string | 
$content_type = "content_type_example"; // string | 
$body = new \Swagger\Client\Model\GetlistofusertradesRequest(); // \Swagger\Client\Model\GetlistofusertradesRequest | 

try {
    $apiInstance->usersReportPost($token, $r, $accept, $content_type, $body);
} catch (Exception $e) {
    echo 'Exception when calling TradesApi->usersReportPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **r** | **int**|  |
 **accept** | **string**|  |
 **content_type** | **string**|  |
 **body** | [**\Swagger\Client\Model\GetlistofusertradesRequest**](../Model/GetlistofusertradesRequest.md)|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

