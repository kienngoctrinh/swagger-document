# Laravel-Swagger Document
## Cài đặt package
```
composer require "darkaonline/l5-swagger"
```
```
php artisan vendor:publish --provider "L5Swagger\L5SwaggerServiceProvider"
```
## Chỉnh sửa config
Mở `file config/l5-swagger.php`, đổi: <br>
`'format_to_use_for_docs' => env('L5_FORMAT_TO_USE_FOR_DOCS', 'json')`
<br>
=>
<br>
`'format_to_use_for_docs' => env('L5_FORMAT_TO_USE_FOR_DOCS', 'yaml')`
<br>
## Tạo file để generate Swagger UI test API
Tạo file `api-docs.yaml` theo đường dẫn `storage/api-docs/api-docs.yaml`
<br>
Lưu ý: Tạo folder `api-docs` trong `storage`
<br>
<br>
Link Swagger UI test API: `{url}/api/documentation`
## Nội dung file `api-docs.yaml`
Tài liệu tham khảo:
<br>
https://viblo.asia/p/tim-hieu-ve-swagger-de-viet-api-XL6lAwbAKek
<br>
https://editor.swagger.io/
<br>
CRUD bảng `products:`
<br>
https://docs.google.com/document/d/1UVLjEJyz_KGpQcLtm8XPAwxNz9-_NppglqcDPmLtTp4/edit?usp=sharing
