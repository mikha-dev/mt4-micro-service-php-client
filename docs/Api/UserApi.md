# Swagger\Client\UserApi

All URIs are relative to *https://apps.noorcm.com:6502/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**5069Get**](UserApi.md#5069Get) | **GET** /5069 | Get user margin
[**userAddPost**](UserApi.md#userAddPost) | **POST** /user/add | Create user
[**userByUserLoginDelete**](UserApi.md#userByUserLoginDelete) | **DELETE** /user/{user_login} | Delete user
[**userByUserLoginGet**](UserApi.md#userByUserLoginGet) | **GET** /user/{user_login} | Get user by user login
[**userDepositPost**](UserApi.md#userDepositPost) | **POST** /user/deposit | Deposit account
[**userResetPwdPost**](UserApi.md#userResetPwdPost) | **POST** /user/reset_pwd | Reset password
[**userUpdatePost**](UserApi.md#userUpdatePost) | **POST** /user/update | Update user
[**userWithdrawPost**](UserApi.md#userWithdrawPost) | **POST** /user/withdraw | Withdraw account


# **5069Get**
> 5069Get($token)

Get user margin

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 

try {
    $apiInstance->5069Get($token);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->5069Get: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userAddPost**
> userAddPost($token, $accept, $content_type, $body)

Create user

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$accept = "accept_example"; // string | 
$content_type = "content_type_example"; // string | 
$body = new \Swagger\Client\Model\CreateuserRequest(); // \Swagger\Client\Model\CreateuserRequest | 

try {
    $apiInstance->userAddPost($token, $accept, $content_type, $body);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userAddPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **accept** | **string**|  |
 **content_type** | **string**|  |
 **body** | [**\Swagger\Client\Model\CreateuserRequest**](../Model/CreateuserRequest.md)|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userByUserLoginDelete**
> userByUserLoginDelete($token, $user_login, $accept)

Delete user

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$user_login = 56; // int | 
$accept = "accept_example"; // string | 

try {
    $apiInstance->userByUserLoginDelete($token, $user_login, $accept);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userByUserLoginDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **user_login** | **int**|  |
 **accept** | **string**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userByUserLoginGet**
> userByUserLoginGet($token, $user_login, $accept)

Get user by user login

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$user_login = 56; // int | 
$accept = "accept_example"; // string | 

try {
    $apiInstance->userByUserLoginGet($token, $user_login, $accept);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userByUserLoginGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **user_login** | **int**|  |
 **accept** | **string**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userDepositPost**
> \Swagger\Client\Model\Depositaccount userDepositPost($token, $accept, $content_type, $body)

Deposit account

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$accept = "accept_example"; // string | 
$content_type = "content_type_example"; // string | 
$body = new \Swagger\Client\Model\DepositaccountRequest(); // \Swagger\Client\Model\DepositaccountRequest | 

try {
    $result = $apiInstance->userDepositPost($token, $accept, $content_type, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userDepositPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **accept** | **string**|  |
 **content_type** | **string**|  |
 **body** | [**\Swagger\Client\Model\DepositaccountRequest**](../Model/DepositaccountRequest.md)|  |

### Return type

[**\Swagger\Client\Model\Depositaccount**](../Model/Depositaccount.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userResetPwdPost**
> userResetPwdPost($token, $accept, $content_type, $body)

Reset password

Reset password

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$accept = "accept_example"; // string | 
$content_type = "content_type_example"; // string | 
$body = new \Swagger\Client\Model\ResetpasswordRequest(); // \Swagger\Client\Model\ResetpasswordRequest | 

try {
    $apiInstance->userResetPwdPost($token, $accept, $content_type, $body);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userResetPwdPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **accept** | **string**|  |
 **content_type** | **string**|  |
 **body** | [**\Swagger\Client\Model\ResetpasswordRequest**](../Model/ResetpasswordRequest.md)|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userUpdatePost**
> userUpdatePost($token, $accept, $content_type, $body)

Update user

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$accept = "accept_example"; // string | 
$content_type = "content_type_example"; // string | 
$body = new \Swagger\Client\Model\UpdateuserRequest(); // \Swagger\Client\Model\UpdateuserRequest | 

try {
    $apiInstance->userUpdatePost($token, $accept, $content_type, $body);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userUpdatePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **accept** | **string**|  |
 **content_type** | **string**|  |
 **body** | [**\Swagger\Client\Model\UpdateuserRequest**](../Model/UpdateuserRequest.md)|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **userWithdrawPost**
> userWithdrawPost($token, $accept, $content_type, $body)

Withdraw account

Withdraw account

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$accept = "accept_example"; // string | 
$content_type = "content_type_example"; // string | 
$body = new \Swagger\Client\Model\WithdrawaccountRequest(); // \Swagger\Client\Model\WithdrawaccountRequest | 

try {
    $apiInstance->userWithdrawPost($token, $accept, $content_type, $body);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->userWithdrawPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **accept** | **string**|  |
 **content_type** | **string**|  |
 **body** | [**\Swagger\Client\Model\WithdrawaccountRequest**](../Model/WithdrawaccountRequest.md)|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

