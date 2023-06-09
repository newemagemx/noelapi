# Project: Noel  Shajris API
# 📁 Collection: Auth 


## End-point: Generate auth token
### Method: POST
>```
>{{baseUrl}}/jwt-auth/v1/token
>```
### Body (**raw**)

```json
{
    "username":"USER",
    "password":"PASSWORD"
}
```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Validate Token
Retrieving posts
### Method: POST
>```
>{{baseUrl}}/jwt-auth/v1/token/validate
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
# 📁 Collection: WooCommerce 

## 📁 Collection: {id} 


## End-point: /wc/v3/coupons/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/coupons/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/coupons/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|code|<string>|text|
|amount|<string>|text|
|discount_type|["<string>","<string>"]|text|
|description|<string>|text|
|date_expires|<string>|text|
|date_expires_gmt|<string>|text|
|individual_use|<string>|text|
|product_ids|<string>|text|
|excluded_product_ids|<string>|text|
|usage_limit|<string>|text|
|usage_limit_per_user|<string>|text|
|limit_usage_to_x_items|<string>|text|
|free_shipping|<string>|text|
|product_categories|<string>|text|
|excluded_product_categories|<string>|text|
|exclude_sale_items|<string>|text|
|minimum_amount|<string>|text|
|maximum_amount|<string>|text|
|email_restrictions|<string>|text|
|meta_data|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/coupons/:id?code=<string>&amount=<string>&discount_type=<string>&discount_type=<string>&description=<string>&date_expires=<string>&date_expires_gmt=<string>&individual_use=<string>&product_ids=<string>&excluded_product_ids=<string>&usage_limit=<string>&usage_limit_per_user=<string>&limit_usage_to_x_items=<string>&free_shipping=<string>&product_categories=<string>&excluded_product_categories=<string>&exclude_sale_items=<string>&minimum_amount=<string>&maximum_amount=<string>&email_restrictions=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|code|<string>|
|amount|<string>|
|discount_type|<string>|
|discount_type|<string>|
|description|<string>|
|date_expires|<string>|
|date_expires_gmt|<string>|
|individual_use|<string>|
|product_ids|<string>|
|excluded_product_ids|<string>|
|usage_limit|<string>|
|usage_limit_per_user|<string>|
|limit_usage_to_x_items|<string>|
|free_shipping|<string>|
|product_categories|<string>|
|excluded_product_categories|<string>|
|exclude_sale_items|<string>|
|minimum_amount|<string>|
|maximum_amount|<string>|
|email_restrictions|<string>|
|meta_data|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/coupons/:id?code=<string>&amount=<string>&discount_type=<string>&discount_type=<string>&description=<string>&date_expires=<string>&date_expires_gmt=<string>&individual_use=<string>&product_ids=<string>&excluded_product_ids=<string>&usage_limit=<string>&usage_limit_per_user=<string>&limit_usage_to_x_items=<string>&free_shipping=<string>&product_categories=<string>&excluded_product_categories=<string>&exclude_sale_items=<string>&minimum_amount=<string>&maximum_amount=<string>&email_restrictions=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|code|<string>|
|amount|<string>|
|discount_type|<string>|
|discount_type|<string>|
|description|<string>|
|date_expires|<string>|
|date_expires_gmt|<string>|
|individual_use|<string>|
|product_ids|<string>|
|excluded_product_ids|<string>|
|usage_limit|<string>|
|usage_limit_per_user|<string>|
|limit_usage_to_x_items|<string>|
|free_shipping|<string>|
|product_categories|<string>|
|excluded_product_categories|<string>|
|exclude_sale_items|<string>|
|minimum_amount|<string>|
|maximum_amount|<string>|
|email_restrictions|<string>|
|meta_data|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/coupons/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: batch 


## End-point: /wc/v3/coupons/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/coupons/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|code|<string>|text|
|amount|<string>|text|
|discount_type|["<string>","<string>"]|text|
|description|<string>|text|
|date_expires|<string>|text|
|date_expires_gmt|<string>|text|
|individual_use|<string>|text|
|product_ids|<string>|text|
|excluded_product_ids|<string>|text|
|usage_limit|<string>|text|
|usage_limit_per_user|<string>|text|
|limit_usage_to_x_items|<string>|text|
|free_shipping|<string>|text|
|product_categories|<string>|text|
|excluded_product_categories|<string>|text|
|exclude_sale_items|<string>|text|
|minimum_amount|<string>|text|
|maximum_amount|<string>|text|
|email_restrictions|<string>|text|
|meta_data|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/coupons/batch?code=<string>&amount=<string>&discount_type=<string>&discount_type=<string>&description=<string>&date_expires=<string>&date_expires_gmt=<string>&individual_use=<string>&product_ids=<string>&excluded_product_ids=<string>&usage_limit=<string>&usage_limit_per_user=<string>&limit_usage_to_x_items=<string>&free_shipping=<string>&product_categories=<string>&excluded_product_categories=<string>&exclude_sale_items=<string>&minimum_amount=<string>&maximum_amount=<string>&email_restrictions=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|code|<string>|
|amount|<string>|
|discount_type|<string>|
|discount_type|<string>|
|description|<string>|
|date_expires|<string>|
|date_expires_gmt|<string>|
|individual_use|<string>|
|product_ids|<string>|
|excluded_product_ids|<string>|
|usage_limit|<string>|
|usage_limit_per_user|<string>|
|limit_usage_to_x_items|<string>|
|free_shipping|<string>|
|product_categories|<string>|
|excluded_product_categories|<string>|
|exclude_sale_items|<string>|
|minimum_amount|<string>|
|maximum_amount|<string>|
|email_restrictions|<string>|
|meta_data|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/coupons/batch?code=<string>&amount=<string>&discount_type=<string>&discount_type=<string>&description=<string>&date_expires=<string>&date_expires_gmt=<string>&individual_use=<string>&product_ids=<string>&excluded_product_ids=<string>&usage_limit=<string>&usage_limit_per_user=<string>&limit_usage_to_x_items=<string>&free_shipping=<string>&product_categories=<string>&excluded_product_categories=<string>&exclude_sale_items=<string>&minimum_amount=<string>&maximum_amount=<string>&email_restrictions=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|code|<string>|
|amount|<string>|
|discount_type|<string>|
|discount_type|<string>|
|description|<string>|
|date_expires|<string>|
|date_expires_gmt|<string>|
|individual_use|<string>|
|product_ids|<string>|
|excluded_product_ids|<string>|
|usage_limit|<string>|
|usage_limit_per_user|<string>|
|limit_usage_to_x_items|<string>|
|free_shipping|<string>|
|product_categories|<string>|
|excluded_product_categories|<string>|
|exclude_sale_items|<string>|
|minimum_amount|<string>|
|maximum_amount|<string>|
|email_restrictions|<string>|
|meta_data|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons
### Method: GET
>```
>{{baseUrl}}/wc/v3/coupons?context=view&context=view&page=<string>&per_page=<string>&search=<string>&after=<dateTime>&before=<dateTime>&exclude=<string>&include=<string>&offset=<string>&order=desc&order=desc&orderby=date&orderby=date&code=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|code|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons
### Method: POST
>```
>{{baseUrl}}/wc/v3/coupons
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|code|<string>|text|
|amount|<string>|text|
|discount_type|["fixed_cart","fixed_cart"]|text|
|description|<string>|text|
|date_expires|<string>|text|
|date_expires_gmt|<string>|text|
|individual_use|<string>|text|
|product_ids|<string>|text|
|excluded_product_ids|<string>|text|
|usage_limit|<string>|text|
|usage_limit_per_user|<string>|text|
|limit_usage_to_x_items|<string>|text|
|free_shipping|<string>|text|
|product_categories|<string>|text|
|excluded_product_categories|<string>|text|
|exclude_sale_items|<string>|text|
|minimum_amount|<string>|text|
|maximum_amount|<string>|text|
|email_restrictions|<string>|text|
|meta_data|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {order id} 

### 📁 Collection: {id} 


## End-point: /wc/v3/orders/:order_id/notes/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/orders/:order_id/notes/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/notes/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/orders/:order_id/notes/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/notes
### Method: GET
>```
>{{baseUrl}}/wc/v3/orders/:order_id/notes?context=view&context=view&type=any&type=any
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|type|any|
|type|any|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/notes
### Method: POST
>```
>{{baseUrl}}/wc/v3/orders/:order_id/notes
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|note|<string>|text|
|customer_note|<string>|text|
|added_by_user|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
### 📁 Collection: {id} 


## End-point: /wc/v3/orders/:order_id/refunds/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/orders/:order_id/refunds/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/refunds/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/orders/:order_id/refunds/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/refunds
### Method: GET
>```
>{{baseUrl}}/wc/v3/orders/:order_id/refunds?context=view&context=view&page=<string>&per_page=<string>&search=<string>&after=<dateTime>&before=<dateTime>&exclude=<string>&include=<string>&offset=<string>&order=desc&order=desc&orderby=date&orderby=date&parent=<string>&parent_exclude=<string>&dp=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|parent|<string>|
|parent_exclude|<string>|
|dp|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/refunds
### Method: POST
>```
>{{baseUrl}}/wc/v3/orders/:order_id/refunds
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|amount|<string>|text|
|reason|<string>|text|
|refunded_by|<string>|text|
|meta_data|<string>|text|
|api_refund|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {id} 


## End-point: /wc/v3/orders/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/orders/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/orders/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|parent_id|<string>|text|
|status|["<string>","<string>"]|text|
|currency|["<string>","<string>"]|text|
|customer_id|<string>|text|
|customer_note|<string>|text|
|billing|<string>|text|
|shipping|<string>|text|
|payment_method|<string>|text|
|payment_method_title|<string>|text|
|transaction_id|<string>|text|
|meta_data|<string>|text|
|line_items|<string>|text|
|shipping_lines|<string>|text|
|fee_lines|<string>|text|
|coupon_lines|<string>|text|
|set_paid|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/orders/:id?parent_id=<string>&status=<string>&status=<string>&currency=<string>&currency=<string>&customer_id=<string>&customer_note=<string>&billing=<string>&shipping=<string>&payment_method=<string>&payment_method_title=<string>&transaction_id=<string>&meta_data=<string>&line_items=<string>&shipping_lines=<string>&fee_lines=<string>&coupon_lines=<string>&set_paid=<string>
>```
### Query Params

|Param|value|
|---|---|
|parent_id|<string>|
|status|<string>|
|status|<string>|
|currency|<string>|
|currency|<string>|
|customer_id|<string>|
|customer_note|<string>|
|billing|<string>|
|shipping|<string>|
|payment_method|<string>|
|payment_method_title|<string>|
|transaction_id|<string>|
|meta_data|<string>|
|line_items|<string>|
|shipping_lines|<string>|
|fee_lines|<string>|
|coupon_lines|<string>|
|set_paid|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/orders/:id?parent_id=<string>&status=<string>&status=<string>&currency=<string>&currency=<string>&customer_id=<string>&customer_note=<string>&billing=<string>&shipping=<string>&payment_method=<string>&payment_method_title=<string>&transaction_id=<string>&meta_data=<string>&line_items=<string>&shipping_lines=<string>&fee_lines=<string>&coupon_lines=<string>&set_paid=<string>
>```
### Query Params

|Param|value|
|---|---|
|parent_id|<string>|
|status|<string>|
|status|<string>|
|currency|<string>|
|currency|<string>|
|customer_id|<string>|
|customer_note|<string>|
|billing|<string>|
|shipping|<string>|
|payment_method|<string>|
|payment_method_title|<string>|
|transaction_id|<string>|
|meta_data|<string>|
|line_items|<string>|
|shipping_lines|<string>|
|fee_lines|<string>|
|coupon_lines|<string>|
|set_paid|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/orders/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: batch 


## End-point: /wc/v3/orders/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/orders/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|parent_id|<string>|text|
|status|["<string>","<string>"]|text|
|currency|["<string>","<string>"]|text|
|customer_id|<string>|text|
|customer_note|<string>|text|
|billing|<string>|text|
|shipping|<string>|text|
|payment_method|<string>|text|
|payment_method_title|<string>|text|
|transaction_id|<string>|text|
|meta_data|<string>|text|
|line_items|<string>|text|
|shipping_lines|<string>|text|
|fee_lines|<string>|text|
|coupon_lines|<string>|text|
|set_paid|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/orders/batch?parent_id=<string>&status=<string>&status=<string>&currency=<string>&currency=<string>&customer_id=<string>&customer_note=<string>&billing=<string>&shipping=<string>&payment_method=<string>&payment_method_title=<string>&transaction_id=<string>&meta_data=<string>&line_items=<string>&shipping_lines=<string>&fee_lines=<string>&coupon_lines=<string>&set_paid=<string>
>```
### Query Params

|Param|value|
|---|---|
|parent_id|<string>|
|status|<string>|
|status|<string>|
|currency|<string>|
|currency|<string>|
|customer_id|<string>|
|customer_note|<string>|
|billing|<string>|
|shipping|<string>|
|payment_method|<string>|
|payment_method_title|<string>|
|transaction_id|<string>|
|meta_data|<string>|
|line_items|<string>|
|shipping_lines|<string>|
|fee_lines|<string>|
|coupon_lines|<string>|
|set_paid|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/orders/batch?parent_id=<string>&status=<string>&status=<string>&currency=<string>&currency=<string>&customer_id=<string>&customer_note=<string>&billing=<string>&shipping=<string>&payment_method=<string>&payment_method_title=<string>&transaction_id=<string>&meta_data=<string>&line_items=<string>&shipping_lines=<string>&fee_lines=<string>&coupon_lines=<string>&set_paid=<string>
>```
### Query Params

|Param|value|
|---|---|
|parent_id|<string>|
|status|<string>|
|status|<string>|
|currency|<string>|
|currency|<string>|
|customer_id|<string>|
|customer_note|<string>|
|billing|<string>|
|shipping|<string>|
|payment_method|<string>|
|payment_method_title|<string>|
|transaction_id|<string>|
|meta_data|<string>|
|line_items|<string>|
|shipping_lines|<string>|
|fee_lines|<string>|
|coupon_lines|<string>|
|set_paid|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders
### Method: GET
>```
>{{baseUrl}}/wc/v3/orders?context=view&context=view&page=<string>&per_page=<string>&search=<string>&after=<dateTime>&before=<dateTime>&exclude=<string>&include=<string>&offset=<string>&order=desc&order=desc&orderby=date&orderby=date&parent=<string>&parent_exclude=<string>&status=<string>&customer=<string>&product=<string>&dp=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|parent|<string>|
|parent_exclude|<string>|
|status|<string>|
|customer|<string>|
|product|<string>|
|dp|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders
### Method: POST
>```
>{{baseUrl}}/wc/v3/orders
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|parent_id|<string>|text|
|status|["pending","pending"]|text|
|currency|["USD","USD"]|text|
|customer_id|<string>|text|
|customer_note|<string>|text|
|billing|<string>|text|
|shipping|<string>|text|
|payment_method|<string>|text|
|payment_method_title|<string>|text|
|transaction_id|<string>|text|
|meta_data|<string>|text|
|line_items|<string>|text|
|shipping_lines|<string>|text|
|fee_lines|<string>|text|
|coupon_lines|<string>|text|
|set_paid|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: attributes 

### 📁 Collection: {id} 


## End-point: /wc/v3/products/attributes/:attribute_id/terms/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|
|menu_order|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/:id?name=<string>&slug=<string>&description=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|
|menu_order|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/:id?name=<string>&slug=<string>&description=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|
|menu_order|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
### 📁 Collection: batch 


## End-point: /wc/v3/products/attributes/:attribute_id/terms/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|
|menu_order|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/batch?name=<string>&slug=<string>&description=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|
|menu_order|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms/batch?name=<string>&slug=<string>&description=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|
|menu_order|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms?context=view&context=view&page=<string>&per_page=<string>&search=<string>&exclude=<string>&include=<string>&order=asc&order=asc&orderby=name&orderby=name&hide_empty=<string>&parent=<string>&product=<string>&slug=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|exclude|<string>|
|include|<string>|
|order|asc|
|order|asc|
|orderby|name|
|orderby|name|
|hide_empty|<string>|
|parent|<string>|
|product|<string>|
|slug|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:attribute_id/terms
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/attributes/:attribute_id/terms
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|
|menu_order|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/attributes/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/attributes/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|type|["<string>","<string>"]|text|
|order_by|["<string>","<string>"]|text|
|has_archives|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/attributes/:id?name=<string>&slug=<string>&type=<string>&type=<string>&order_by=<string>&order_by=<string>&has_archives=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|type|<string>|
|type|<string>|
|order_by|<string>|
|order_by|<string>|
|has_archives|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/attributes/:id?name=<string>&slug=<string>&type=<string>&type=<string>&order_by=<string>&order_by=<string>&has_archives=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|type|<string>|
|type|<string>|
|order_by|<string>|
|order_by|<string>|
|has_archives|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/attributes/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/attributes/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|type|["<string>","<string>"]|text|
|order_by|["<string>","<string>"]|text|
|has_archives|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/attributes/batch?name=<string>&slug=<string>&type=<string>&type=<string>&order_by=<string>&order_by=<string>&has_archives=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|type|<string>|
|type|<string>|
|order_by|<string>|
|order_by|<string>|
|has_archives|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/attributes/batch?name=<string>&slug=<string>&type=<string>&type=<string>&order_by=<string>&order_by=<string>&has_archives=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|type|<string>|
|type|<string>|
|order_by|<string>|
|order_by|<string>|
|has_archives|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/attributes?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/attributes
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/attributes
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|type|["select","select"]|text|
|order_by|["menu_order","menu_order"]|text|
|has_archives|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: categories 


## End-point: /wc/v3/products/categories/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/categories/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/categories/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|parent|<string>|text|
|description|<string>|text|
|display|["<string>","<string>"]|text|
|image|<string>|text|
|menu_order|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/categories/:id?name=<string>&slug=<string>&parent=<string>&description=<string>&display=<string>&display=<string>&image=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|parent|<string>|
|description|<string>|
|display|<string>|
|display|<string>|
|image|<string>|
|menu_order|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/categories/:id?name=<string>&slug=<string>&parent=<string>&description=<string>&display=<string>&display=<string>&image=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|parent|<string>|
|description|<string>|
|display|<string>|
|display|<string>|
|image|<string>|
|menu_order|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/categories/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/categories/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|parent|<string>|text|
|description|<string>|text|
|display|["<string>","<string>"]|text|
|image|<string>|text|
|menu_order|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/categories/batch?name=<string>&slug=<string>&parent=<string>&description=<string>&display=<string>&display=<string>&image=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|parent|<string>|
|description|<string>|
|display|<string>|
|display|<string>|
|image|<string>|
|menu_order|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/categories/batch?name=<string>&slug=<string>&parent=<string>&description=<string>&display=<string>&display=<string>&image=<string>&menu_order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|parent|<string>|
|description|<string>|
|display|<string>|
|display|<string>|
|image|<string>|
|menu_order|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/categories?context=view&context=view&page=<string>&per_page=<string>&search=<string>&exclude=<string>&include=<string>&order=asc&order=asc&orderby=name&orderby=name&hide_empty=<string>&parent=<string>&product=<string>&slug=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|exclude|<string>|
|include|<string>|
|order|asc|
|order|asc|
|orderby|name|
|orderby|name|
|hide_empty|<string>|
|parent|<string>|
|product|<string>|
|slug|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/categories
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|parent|<string>|text|
|description|<string>|text|
|display|["default","default"]|text|
|image|<string>|text|
|menu_order|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: reviews 


## End-point: /wc/v3/products/reviews/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/reviews/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/reviews/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|product_id|<string>|text|
|status|["<string>","<string>"]|text|
|reviewer|<string>|text|
|reviewer_email|<email>|text|
|review|<string>|text|
|rating|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/reviews/:id?product_id=<string>&status=<string>&status=<string>&reviewer=<string>&reviewer_email=<email>&review=<string>&rating=<string>
>```
### Query Params

|Param|value|
|---|---|
|product_id|<string>|
|status|<string>|
|status|<string>|
|reviewer|<string>|
|reviewer_email|<email>|
|review|<string>|
|rating|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/reviews/:id?product_id=<string>&status=<string>&status=<string>&reviewer=<string>&reviewer_email=<email>&review=<string>&rating=<string>
>```
### Query Params

|Param|value|
|---|---|
|product_id|<string>|
|status|<string>|
|status|<string>|
|reviewer|<string>|
|reviewer_email|<email>|
|review|<string>|
|rating|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/reviews/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/reviews/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|product_id|<string>|text|
|status|["<string>","<string>"]|text|
|reviewer|<string>|text|
|reviewer_email|<email>|text|
|review|<string>|text|
|rating|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/reviews/batch?product_id=<string>&status=<string>&status=<string>&reviewer=<string>&reviewer_email=<email>&review=<string>&rating=<string>
>```
### Query Params

|Param|value|
|---|---|
|product_id|<string>|
|status|<string>|
|status|<string>|
|reviewer|<string>|
|reviewer_email|<email>|
|review|<string>|
|rating|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/reviews/batch?product_id=<string>&status=<string>&status=<string>&reviewer=<string>&reviewer_email=<email>&review=<string>&rating=<string>
>```
### Query Params

|Param|value|
|---|---|
|product_id|<string>|
|status|<string>|
|status|<string>|
|reviewer|<string>|
|reviewer_email|<email>|
|review|<string>|
|rating|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/reviews?context=view&context=view&page=<string>&per_page=<string>&search=<string>&after=<dateTime>&before=<dateTime>&exclude=<string>&include=<string>&offset=<string>&order=desc&order=desc&orderby=date_gmt&orderby=date_gmt&reviewer=<string>&reviewer_exclude=<string>&reviewer_email=<email>&product=<string>&status=approved&status=approved
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date_gmt|
|orderby|date_gmt|
|reviewer|<string>|
|reviewer_exclude|<string>|
|reviewer_email|<email>|
|product|<string>|
|status|approved|
|status|approved|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/reviews
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/reviews
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|product_id|<string>|text|
|reviewer|<string>|text|
|reviewer_email|<string>|text|
|review|<string>|text|
|status|["approved","approved"]|text|
|rating|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: shipping classes 


## End-point: /wc/v3/products/shipping_classes/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/:id?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/:id?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/batch?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/shipping_classes/batch?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/shipping_classes?context=view&context=view&page=<string>&per_page=<string>&search=<string>&exclude=<string>&include=<string>&offset=<string>&order=asc&order=asc&orderby=name&orderby=name&hide_empty=<string>&product=<string>&slug=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|asc|
|order|asc|
|orderby|name|
|orderby|name|
|hide_empty|<string>|
|product|<string>|
|slug|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/shipping_classes
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/shipping_classes
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: tags 


## End-point: /wc/v3/products/tags/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/tags/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/tags/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/tags/:id?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/tags/:id?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/tags/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/tags/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/tags/batch?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/tags/batch?name=<string>&slug=<string>&description=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|description|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/tags?context=view&context=view&page=<string>&per_page=<string>&search=<string>&exclude=<string>&include=<string>&offset=<string>&order=asc&order=asc&orderby=name&orderby=name&hide_empty=<string>&product=<string>&slug=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|asc|
|order|asc|
|orderby|name|
|orderby|name|
|hide_empty|<string>|
|product|<string>|
|slug|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/tags
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/tags
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|description|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {id} 


## End-point: /wc/v3/products/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|date_created|<string>|text|
|date_created_gmt|<string>|text|
|type|["<string>","<string>"]|text|
|status|["<string>","<string>"]|text|
|featured|<string>|text|
|catalog_visibility|["<string>","<string>"]|text|
|description|<string>|text|
|short_description|<string>|text|
|sku|<string>|text|
|regular_price|<string>|text|
|sale_price|<string>|text|
|date_on_sale_from|<string>|text|
|date_on_sale_from_gmt|<string>|text|
|date_on_sale_to|<string>|text|
|date_on_sale_to_gmt|<string>|text|
|virtual|<string>|text|
|downloadable|<string>|text|
|downloads|<string>|text|
|download_limit|<string>|text|
|download_expiry|<string>|text|
|external_url|<uri>|text|
|button_text|<string>|text|
|tax_status|["<string>","<string>"]|text|
|tax_class|<string>|text|
|manage_stock|<string>|text|
|stock_quantity|<string>|text|
|stock_status|["<string>","<string>"]|text|
|backorders|["<string>","<string>"]|text|
|sold_individually|<string>|text|
|weight|<string>|text|
|dimensions|<string>|text|
|shipping_class|<string>|text|
|reviews_allowed|<string>|text|
|upsell_ids|<string>|text|
|cross_sell_ids|<string>|text|
|parent_id|<string>|text|
|purchase_note|<string>|text|
|categories|<string>|text|
|tags|<string>|text|
|images|<string>|text|
|attributes|<string>|text|
|default_attributes|<string>|text|
|menu_order|<string>|text|
|meta_data|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/:id?name=<string>&slug=<string>&date_created=<string>&date_created_gmt=<string>&type=<string>&type=<string>&status=<string>&status=<string>&featured=<string>&catalog_visibility=<string>&catalog_visibility=<string>&description=<string>&short_description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&external_url=<uri>&button_text=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&sold_individually=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&reviews_allowed=<string>&upsell_ids=<string>&cross_sell_ids=<string>&parent_id=<string>&purchase_note=<string>&categories=<string>&tags=<string>&images=<string>&attributes=<string>&default_attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|date_created|<string>|
|date_created_gmt|<string>|
|type|<string>|
|type|<string>|
|status|<string>|
|status|<string>|
|featured|<string>|
|catalog_visibility|<string>|
|catalog_visibility|<string>|
|description|<string>|
|short_description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|external_url|<uri>|
|button_text|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|sold_individually|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|reviews_allowed|<string>|
|upsell_ids|<string>|
|cross_sell_ids|<string>|
|parent_id|<string>|
|purchase_note|<string>|
|categories|<string>|
|tags|<string>|
|images|<string>|
|attributes|<string>|
|default_attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/:id?name=<string>&slug=<string>&date_created=<string>&date_created_gmt=<string>&type=<string>&type=<string>&status=<string>&status=<string>&featured=<string>&catalog_visibility=<string>&catalog_visibility=<string>&description=<string>&short_description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&external_url=<uri>&button_text=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&sold_individually=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&reviews_allowed=<string>&upsell_ids=<string>&cross_sell_ids=<string>&parent_id=<string>&purchase_note=<string>&categories=<string>&tags=<string>&images=<string>&attributes=<string>&default_attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|date_created|<string>|
|date_created_gmt|<string>|
|type|<string>|
|type|<string>|
|status|<string>|
|status|<string>|
|featured|<string>|
|catalog_visibility|<string>|
|catalog_visibility|<string>|
|description|<string>|
|short_description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|external_url|<uri>|
|button_text|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|sold_individually|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|reviews_allowed|<string>|
|upsell_ids|<string>|
|cross_sell_ids|<string>|
|parent_id|<string>|
|purchase_note|<string>|
|categories|<string>|
|tags|<string>|
|images|<string>|
|attributes|<string>|
|default_attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: batch 


## End-point: /wc/v3/products/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|date_created|<string>|text|
|date_created_gmt|<string>|text|
|type|["<string>","<string>"]|text|
|status|["<string>","<string>"]|text|
|featured|<string>|text|
|catalog_visibility|["<string>","<string>"]|text|
|description|<string>|text|
|short_description|<string>|text|
|sku|<string>|text|
|regular_price|<string>|text|
|sale_price|<string>|text|
|date_on_sale_from|<string>|text|
|date_on_sale_from_gmt|<string>|text|
|date_on_sale_to|<string>|text|
|date_on_sale_to_gmt|<string>|text|
|virtual|<string>|text|
|downloadable|<string>|text|
|downloads|<string>|text|
|download_limit|<string>|text|
|download_expiry|<string>|text|
|external_url|<uri>|text|
|button_text|<string>|text|
|tax_status|["<string>","<string>"]|text|
|tax_class|<string>|text|
|manage_stock|<string>|text|
|stock_quantity|<string>|text|
|stock_status|["<string>","<string>"]|text|
|backorders|["<string>","<string>"]|text|
|sold_individually|<string>|text|
|weight|<string>|text|
|dimensions|<string>|text|
|shipping_class|<string>|text|
|reviews_allowed|<string>|text|
|upsell_ids|<string>|text|
|cross_sell_ids|<string>|text|
|parent_id|<string>|text|
|purchase_note|<string>|text|
|categories|<string>|text|
|tags|<string>|text|
|images|<string>|text|
|attributes|<string>|text|
|default_attributes|<string>|text|
|menu_order|<string>|text|
|meta_data|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/batch?name=<string>&slug=<string>&date_created=<string>&date_created_gmt=<string>&type=<string>&type=<string>&status=<string>&status=<string>&featured=<string>&catalog_visibility=<string>&catalog_visibility=<string>&description=<string>&short_description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&external_url=<uri>&button_text=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&sold_individually=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&reviews_allowed=<string>&upsell_ids=<string>&cross_sell_ids=<string>&parent_id=<string>&purchase_note=<string>&categories=<string>&tags=<string>&images=<string>&attributes=<string>&default_attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|date_created|<string>|
|date_created_gmt|<string>|
|type|<string>|
|type|<string>|
|status|<string>|
|status|<string>|
|featured|<string>|
|catalog_visibility|<string>|
|catalog_visibility|<string>|
|description|<string>|
|short_description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|external_url|<uri>|
|button_text|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|sold_individually|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|reviews_allowed|<string>|
|upsell_ids|<string>|
|cross_sell_ids|<string>|
|parent_id|<string>|
|purchase_note|<string>|
|categories|<string>|
|tags|<string>|
|images|<string>|
|attributes|<string>|
|default_attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/batch?name=<string>&slug=<string>&date_created=<string>&date_created_gmt=<string>&type=<string>&type=<string>&status=<string>&status=<string>&featured=<string>&catalog_visibility=<string>&catalog_visibility=<string>&description=<string>&short_description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&external_url=<uri>&button_text=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&sold_individually=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&reviews_allowed=<string>&upsell_ids=<string>&cross_sell_ids=<string>&parent_id=<string>&purchase_note=<string>&categories=<string>&tags=<string>&images=<string>&attributes=<string>&default_attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|slug|<string>|
|date_created|<string>|
|date_created_gmt|<string>|
|type|<string>|
|type|<string>|
|status|<string>|
|status|<string>|
|featured|<string>|
|catalog_visibility|<string>|
|catalog_visibility|<string>|
|description|<string>|
|short_description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|external_url|<uri>|
|button_text|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|sold_individually|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|reviews_allowed|<string>|
|upsell_ids|<string>|
|cross_sell_ids|<string>|
|parent_id|<string>|
|purchase_note|<string>|
|categories|<string>|
|tags|<string>|
|images|<string>|
|attributes|<string>|
|default_attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {product id}/variations 


## End-point: /wc/v3/products/:product_id/variations/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|description|<string>|text|
|sku|<string>|text|
|regular_price|<string>|text|
|sale_price|<string>|text|
|date_on_sale_from|<string>|text|
|date_on_sale_from_gmt|<string>|text|
|date_on_sale_to|<string>|text|
|date_on_sale_to_gmt|<string>|text|
|status|["<string>","<string>"]|text|
|virtual|<string>|text|
|downloadable|<string>|text|
|downloads|<string>|text|
|download_limit|<string>|text|
|download_expiry|<string>|text|
|tax_status|["<string>","<string>"]|text|
|tax_class|<string>|text|
|manage_stock|<string>|text|
|stock_quantity|<string>|text|
|stock_status|["<string>","<string>"]|text|
|backorders|["<string>","<string>"]|text|
|weight|<string>|text|
|dimensions|<string>|text|
|shipping_class|<string>|text|
|image|<string>|text|
|attributes|<string>|text|
|menu_order|<string>|text|
|meta_data|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/:id?description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&status=<string>&status=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&image=<string>&attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|status|<string>|
|status|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|image|<string>|
|attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/:id?description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&status=<string>&status=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&image=<string>&attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|status|<string>|
|status|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|image|<string>|
|attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/batch
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/batch
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|description|<string>|text|
|sku|<string>|text|
|regular_price|<string>|text|
|sale_price|<string>|text|
|date_on_sale_from|<string>|text|
|date_on_sale_from_gmt|<string>|text|
|date_on_sale_to|<string>|text|
|date_on_sale_to_gmt|<string>|text|
|status|["<string>","<string>"]|text|
|virtual|<string>|text|
|downloadable|<string>|text|
|downloads|<string>|text|
|download_limit|<string>|text|
|download_expiry|<string>|text|
|tax_status|["<string>","<string>"]|text|
|tax_class|<string>|text|
|manage_stock|<string>|text|
|stock_quantity|<string>|text|
|stock_status|["<string>","<string>"]|text|
|backorders|["<string>","<string>"]|text|
|weight|<string>|text|
|dimensions|<string>|text|
|shipping_class|<string>|text|
|image|<string>|text|
|attributes|<string>|text|
|menu_order|<string>|text|
|meta_data|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/batch
### Method: PUT
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/batch?description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&status=<string>&status=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&image=<string>&attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|status|<string>|
|status|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|image|<string>|
|attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations/batch
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations/batch?description=<string>&sku=<string>&regular_price=<string>&sale_price=<string>&date_on_sale_from=<string>&date_on_sale_from_gmt=<string>&date_on_sale_to=<string>&date_on_sale_to_gmt=<string>&status=<string>&status=<string>&virtual=<string>&downloadable=<string>&downloads=<string>&download_limit=<string>&download_expiry=<string>&tax_status=<string>&tax_status=<string>&tax_class=<string>&manage_stock=<string>&stock_quantity=<string>&stock_status=<string>&stock_status=<string>&backorders=<string>&backorders=<string>&weight=<string>&dimensions=<string>&shipping_class=<string>&image=<string>&attributes=<string>&menu_order=<string>&meta_data=<string>
>```
### Query Params

|Param|value|
|---|---|
|description|<string>|
|sku|<string>|
|regular_price|<string>|
|sale_price|<string>|
|date_on_sale_from|<string>|
|date_on_sale_from_gmt|<string>|
|date_on_sale_to|<string>|
|date_on_sale_to_gmt|<string>|
|status|<string>|
|status|<string>|
|virtual|<string>|
|downloadable|<string>|
|downloads|<string>|
|download_limit|<string>|
|download_expiry|<string>|
|tax_status|<string>|
|tax_status|<string>|
|tax_class|<string>|
|manage_stock|<string>|
|stock_quantity|<string>|
|stock_status|<string>|
|stock_status|<string>|
|backorders|<string>|
|backorders|<string>|
|weight|<string>|
|dimensions|<string>|
|shipping_class|<string>|
|image|<string>|
|attributes|<string>|
|menu_order|<string>|
|meta_data|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations
### Method: GET
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations?context=view&context=view&page=<string>&per_page=<string>&search=<string>&after=<dateTime>&before=<dateTime>&exclude=<string>&include=<string>&offset=<string>&order=desc&order=desc&orderby=date&orderby=date&parent=<string>&parent_exclude=<string>&slug=<string>&status=any&status=any&sku=<string>&on_sale=<string>&min_price=<string>&max_price=<string>&stock_status=<string>&stock_status=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|parent|<string>|
|parent_exclude|<string>|
|slug|<string>|
|status|any|
|status|any|
|sku|<string>|
|on_sale|<string>|
|min_price|<string>|
|max_price|<string>|
|stock_status|<string>|
|stock_status|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/:product_id/variations
### Method: POST
>```
>{{baseUrl}}/wc/v3/products/:product_id/variations
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|description|<string>|text|
|sku|<string>|text|
|regular_price|<string>|text|
|sale_price|<string>|text|
|date_on_sale_from|<string>|text|
|date_on_sale_from_gmt|<string>|text|
|date_on_sale_to|<string>|text|
|date_on_sale_to_gmt|<string>|text|
|status|["publish","publish"]|text|
|virtual|<string>|text|
|downloadable|<string>|text|
|downloads|<string>|text|
|download_limit|<string>|text|
|download_expiry|<string>|text|
|tax_status|["taxable","taxable"]|text|
|tax_class|<string>|text|
|manage_stock|<string>|text|
|stock_quantity|<string>|text|
|stock_status|["instock","instock"]|text|
|backorders|["no","no"]|text|
|weight|<string>|text|
|dimensions|<string>|text|
|shipping_class|<string>|text|
|image|<string>|text|
|attributes|<string>|text|
|menu_order|<string>|text|
|meta_data|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: Experiences 


## End-point: Retrieve experiences
### Method: GET
>```
>{{newe}}{{wc}}/products?category=28&category=29&category=27&category=53&category=25&category=35&category=30
>```
### Body (**raw**)

```json

```

### Query Params

|Param|value|
|---|---|
|category|28|
|category|29|
|category|27|
|category|53|
|category|25|
|category|35|
|category|30|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: Greetings 


## End-point: Retrieve greetings
### Method: GET
>```
>{{newe}}{{wc}}/products?category=26
>```
### Body (**raw**)

```json

```

### Query Params

|Param|value|
|---|---|
|category|26|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: Merch 


## End-point: Retrieve Merch
### Method: GET
>```
>{{newe}}{{wc}}/products?category=34&category=33&category=31&category=32&category=73
>```
### Body (**raw**)

```json

```

### Query Params

|Param|value|
|---|---|
|category|34|
|category|33|
|category|31|
|category|32|
|category|73|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products
### Method: GET
>```
>{{baseUrl}}/wc/v3/products
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|parent|<string>|
|parent_exclude|<string>|
|slug|<string>|
|status|any|
|status|any|
|type|<string>|
|type|<string>|
|sku|<string>|
|featured|<string>|
|category|<string>|
|tag|<string>|
|shipping_class|<string>|
|attribute|<string>|
|attribute_term|<string>|
|on_sale|<string>|
|min_price|<string>|
|max_price|<string>|
|stock_status|<string>|
|stock_status|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products
### Method: POST
>```
>{{baseUrl}}/wc/v3/products
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|slug|<string>|text|
|date_created|<string>|text|
|date_created_gmt|<string>|text|
|type|["simple","simple"]|text|
|status|["publish","publish"]|text|
|featured|<string>|text|
|catalog_visibility|["visible","visible"]|text|
|description|<string>|text|
|short_description|<string>|text|
|sku|<string>|text|
|regular_price|<string>|text|
|sale_price|<string>|text|
|date_on_sale_from|<string>|text|
|date_on_sale_from_gmt|<string>|text|
|date_on_sale_to|<string>|text|
|date_on_sale_to_gmt|<string>|text|
|virtual|<string>|text|
|downloadable|<string>|text|
|downloads|<string>|text|
|download_limit|<string>|text|
|download_expiry|<string>|text|
|external_url|<uri>|text|
|button_text|<string>|text|
|tax_status|["taxable","taxable"]|text|
|tax_class|<string>|text|
|manage_stock|<string>|text|
|stock_quantity|<string>|text|
|stock_status|["instock","instock"]|text|
|backorders|["no","no"]|text|
|sold_individually|<string>|text|
|weight|<string>|text|
|dimensions|<string>|text|
|shipping_class|<string>|text|
|reviews_allowed|<string>|text|
|upsell_ids|<string>|text|
|cross_sell_ids|<string>|text|
|parent_id|<string>|text|
|purchase_note|<string>|text|
|categories|<string>|text|
|tags|<string>|text|
|images|<string>|text|
|attributes|<string>|text|
|default_attributes|<string>|text|
|menu_order|<string>|text|
|meta_data|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {id} 


## End-point: /wc/v3/shipping/zones/:id/locations
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id/locations
>```
### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id/locations
### Method: POST
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id/locations
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|code|<string>|text|
|type|["<string>","<string>"]|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id/locations
### Method: PUT
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id/locations?code=<string>&type=<string>&type=<string>
>```
### Query Params

|Param|value|
|---|---|
|code|<string>|
|type|<string>|
|type|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id/locations
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id/locations?code=<string>&type=<string>&type=<string>
>```
### Query Params

|Param|value|
|---|---|
|code|<string>|
|type|<string>|
|type|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id
>```
### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|order|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id?name=<string>&order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|order|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id?name=<string>&order=<string>
>```
### Query Params

|Param|value|
|---|---|
|name|<string>|
|order|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/shipping/zones/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {zone id}/methods 


## End-point: /wc/v3/shipping/zones/:zone_id/methods/:instance_id
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods/:instance_id
>```
### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:zone_id/methods/:instance_id
### Method: POST
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods/:instance_id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|order|<string>|text|
|enabled|<string>|text|
|settings|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:zone_id/methods/:instance_id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods/:instance_id?order=<string>&enabled=<string>&settings=<string>
>```
### Query Params

|Param|value|
|---|---|
|order|<string>|
|enabled|<string>|
|settings|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:zone_id/methods/:instance_id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods/:instance_id?order=<string>&enabled=<string>&settings=<string>
>```
### Query Params

|Param|value|
|---|---|
|order|<string>|
|enabled|<string>|
|settings|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:zone_id/methods/:instance_id
### Method: DELETE
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods/:instance_id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:zone_id/methods
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods
>```
### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones/:zone_id/methods
### Method: POST
>```
>{{baseUrl}}/wc/v3/shipping/zones/:zone_id/methods
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|method_id|<string>|text|
|order|<string>|text|
|enabled|<string>|text|
|settings|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping/zones
>```
### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping/zones
### Method: POST
>```
>{{baseUrl}}/wc/v3/shipping/zones
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|name|<string>|text|
|order|<string>|text|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping_methods
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping_methods?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/shipping_methods/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/shipping_methods/:id
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {id} 


## End-point: /wc/v3/payment_gateways/:id
### Method: GET
>```
>{{baseUrl}}/wc/v3/payment_gateways/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/payment_gateways/:id
### Method: POST
>```
>{{baseUrl}}/wc/v3/payment_gateways/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|title|<string>|text|
|description|<string>|text|
|order|<string>|text|
|enabled|<string>|text|
|settings|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/payment_gateways/:id
### Method: PUT
>```
>{{baseUrl}}/wc/v3/payment_gateways/:id?title=<string>&description=<string>&order=<string>&enabled=<string>&settings=<string>
>```
### Query Params

|Param|value|
|---|---|
|title|<string>|
|description|<string>|
|order|<string>|
|enabled|<string>|
|settings|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/payment_gateways/:id
### Method: PATCH
>```
>{{baseUrl}}/wc/v3/payment_gateways/:id?title=<string>&description=<string>&order=<string>&enabled=<string>&settings=<string>
>```
### Query Params

|Param|value|
|---|---|
|title|<string>|
|description|<string>|
|order|<string>|
|enabled|<string>|
|settings|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/payment_gateways
### Method: GET
>```
>{{baseUrl}}/wc/v3/payment_gateways?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
# 📁 Collection: Wordpress 


## End-point: List Users 
|||
|:--|:--
|```context```|Scope under which the request is made; determines fields present in response.<br/>Default: **view**<br/>One of: **view, embed, edit**
|```page```|Current page of the collection.<br/>Default: **1**
|```per_page```|Maximum number of items to be returned in result set.<br/>Default: **10**
|```search```|Limit results to those matching a string.
|```exclude```|Ensure result set excludes specific IDs.
|```include```|Limit result set to specific IDs.
|```offset```|Offset the result set by a specific number of items.
|```order```|Order sort attribute ascending or descending.<br/>Default: **asc**<br/>One of: **asc, desc**
|```orderby```|Sort collection by object attribute.<br/>Default: **name**<br/>One of: **id, include, name, registered_date, slug, include_slugs, email, url**
|```slug```|Limit result set to users with one or more specific slugs.
|```roles```|Limit result set to users matching at least one specific role provided. Accepts csv list or single role.
|```who```|Limit result set to users who are considered authors.<br/>One of: **authors**
### Method: GET
>```
>{{baseUrl}}/wp/v2/users
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Create a User
|||
|:---|:---
|```username```|Login name for the user.<br/>Required: **1**
|```name```|Display name for the user.
|```first_name```|First name for the user.
|```last_name```|Last name for the user.
|```email```|The email address for the user.<br/>Required: **1**
|```url```|URL of the user.
|```description```|Description of the user.
|```locale```|Locale for the user.<br/>One of: **en_US**
|```nickname```|The nickname for the user.
|```slug```|An alphanumeric identifier for the user.
|```roles```|Roles assigned to the user.
|```password```|Password for the user (never included).<br/>Required: **1**
|```meta```|Meta fields.
### Method: POST
>```
>{{baseUrl}}/wp/v2/users
>```
### Body (**raw**)

```json
{
    "username": "",
    "email": "",
    "password": ""
}
```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Retrieve a User
|||
|:---|:---
|```id```|Unique identifier for the user.
|```context```|Scope under which the request is made; determines fields present in response.<br/>Default: **view**<br/>One of: **view, embed, edit**
### Method: GET
>```
>{{baseUrl}}/wp/v2/users/:user_id
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Update a User
|||
|:---|:---
|```id```|Unique identifier for the user.
|```username```|Login name for the user.
|```name```|Display name for the user.
|```first_name```|First name for the user.
|```last_name```|Last name for the user.
|```email```|The email address for the user.
|```url```|URL of the user.
|```description```|Description of the user.
|```locale```|Locale for the user.<br/>One of: **en_US**
|```nickname```|The nickname for the user.
|```slug```|An alphanumeric identifier for the user.
|```roles```|Roles assigned to the user.
|```password```|Password for the user (never included).
|```meta```|Meta fields.
### Method: POST
>```
>{{baseUrl}}/wp/v2/users/:user_id
>```
### Body (**raw**)

```json
{
    "username": "",
    "email": "",
    "password": ""
}
```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Delete User
|||
|:---|:---
|```id```|Unique identifier for the user.
|```force```|Required to be true, as users do not support trashing.
|```reassign```|Reassign the deleted user's posts and links to this user ID.<br/>Required: **1**
### Method: DELETE
>```
>{{baseUrl}}/wp/v2/users/:user_id
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: List greetings
### Method: GET
>```
>{{baseUrl}}/wp/v2/saludo
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Retrieve a greeting
### Method: GET
>```
>{{baseUrl}}/wp/v2/saludo?slug=:nombre-id
>```
### Query Params

|Param|value|
|---|---|
|slug|:nombre-id|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
# 📁 Collection: NS Music 


## End-point: /wc/v3/coupons/:id
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/coupons/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/coupons
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/coupons
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|page|1|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|code|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {order id} 

### 📁 Collection: {id} 


## End-point: /wc/v3/orders/:order_id/notes/:id
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/notes/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/notes/:id
### Method: DELETE
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/notes/:id
>```
### Query Params

|Param|value|
|---|---|
|force|true|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/notes
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/notes?context=view&context=view&type=any&type=any
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|type|any|
|type|any|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/notes
### Method: POST
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/notes
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|note|<string>|text|
|customer_note|<string>|text|
|added_by_user|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
### 📁 Collection: {id} 


## End-point: /wc/v3/orders/:order_id/refunds/:id
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/refunds/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/refunds/:id
### Method: DELETE
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/refunds/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/refunds
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/refunds?context=view&context=view&page=<string>&per_page=<string>&search=<string>&after=<dateTime>&before=<dateTime>&exclude=<string>&include=<string>&offset=<string>&order=desc&order=desc&orderby=date&orderby=date&parent=<string>&parent_exclude=<string>&dp=<string>
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|order|desc|
|orderby|date|
|orderby|date|
|parent|<string>|
|parent_exclude|<string>|
|dp|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:order_id/refunds
### Method: POST
>```
>{{nsmusicUrl}}/wc/v3/orders/:order_id/refunds
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|amount|<string>|text|
|reason|<string>|text|
|refunded_by|<string>|text|
|meta_data|<string>|text|
|api_refund|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: {id} 


## End-point: /wc/v3/orders/:id
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/orders/:id?context=view&context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|context|view|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: POST
>```
>{{nsmusicUrl}}/wc/v3/orders/:id
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|parent_id|<string>|text|
|status|["<string>","<string>"]|text|
|currency|["<string>","<string>"]|text|
|customer_id|<string>|text|
|customer_note|<string>|text|
|billing|<string>|text|
|shipping|<string>|text|
|payment_method|<string>|text|
|payment_method_title|<string>|text|
|transaction_id|<string>|text|
|meta_data|<string>|text|
|line_items|<string>|text|
|shipping_lines|<string>|text|
|fee_lines|<string>|text|
|coupon_lines|<string>|text|
|set_paid|<string>|text|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: PUT
>```
>{{nsmusicUrl}}/wc/v3/orders/:id
>```
### Body (**raw**)

```json
{
    "status": "processing"
}
```

### Query Params

|Param|value|
|---|---|
|parent_id|<string>|
|status|<string>|
|currency|<string>|
|customer_id|<string>|
|customer_note|<string>|
|billing|<string>|
|shipping|<string>|
|payment_method|<string>|
|payment_method_title|<string>|
|transaction_id|<string>|
|meta_data|<string>|
|line_items|<string>|
|shipping_lines|<string>|
|fee_lines|<string>|
|coupon_lines|<string>|
|set_paid|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: PATCH
>```
>{{nsmusicUrl}}/wc/v3/orders/:id?parent_id=<string>&status=<string>&status=<string>&currency=<string>&currency=<string>&customer_id=<string>&customer_note=<string>&billing=<string>&shipping=<string>&payment_method=<string>&payment_method_title=<string>&transaction_id=<string>&meta_data=<string>&line_items=<string>&shipping_lines=<string>&fee_lines=<string>&coupon_lines=<string>&set_paid=<string>
>```
### Query Params

|Param|value|
|---|---|
|parent_id|<string>|
|status|<string>|
|status|<string>|
|currency|<string>|
|currency|<string>|
|customer_id|<string>|
|customer_note|<string>|
|billing|<string>|
|shipping|<string>|
|payment_method|<string>|
|payment_method_title|<string>|
|transaction_id|<string>|
|meta_data|<string>|
|line_items|<string>|
|shipping_lines|<string>|
|fee_lines|<string>|
|coupon_lines|<string>|
|set_paid|<string>|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders/:id
### Method: DELETE
>```
>{{nsmusicUrl}}/wc/v3/orders/:id?force=<string>
>```
### Query Params

|Param|value|
|---|---|
|force|<string>|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/orders?context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|
|page|<string>|
|per_page|<string>|
|search|<string>|
|after|<dateTime>|
|before|<dateTime>|
|exclude|<string>|
|include|<string>|
|offset|<string>|
|order|desc|
|orderby|date|
|parent|<string>|
|parent_exclude|<string>|
|status|<string>|
|customer|<string>|
|product|<string>|
|dp|<string>|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/orders
### Method: POST
>```
>{{nsmusicUrl}}/wc/v3/orders
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|multipart/form-data|


### Body formdata

|Param|value|Type|
|---|---|---|
|parent_id|<string>|text|
|status|["pending","pending"]|text|
|currency|["USD","USD"]|text|
|customer_id|<string>|text|
|customer_note|<string>|text|
|billing|<string>|text|
|shipping|<string>|text|
|payment_method|<string>|text|
|payment_method_title|<string>|text|
|transaction_id|<string>|text|
|meta_data|<string>|text|
|line_items|<string>|text|
|shipping_lines|<string>|text|
|fee_lines|<string>|text|
|coupon_lines|<string>|text|
|set_paid|<string>|text|


### Response: 404
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: categories 


## End-point: /wc/v3/products/categories
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/products/categories
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/products/categories/:id
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/products/categories/:id
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: Albums 


## End-point: Retrieve all albums
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/products/?category=21
>```
### Query Params

|Param|value|
|---|---|
|category|21|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Retrieve one album
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/products/:id
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
## 📁 Collection: Singles 


## End-point: Retrieve all singles
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/products/?category=22
>```
### Query Params

|Param|value|
|---|---|
|category|22|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: Retrieve one single
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/products/:trackId
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/payment_gateways/:id
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/payment_gateways/:id?context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|


### Response: 200
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: /wc/v3/payment_gateways
### Method: GET
>```
>{{nsmusicUrl}}/wc/v3/payment_gateways?context=view
>```
### Query Params

|Param|value|
|---|---|
|context|view|


### Response: 400
```json

```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
_________________________________________________
Powered By: [postman-to-markdown](https://github.com/bautistaj/postman-to-markdown/)
