# API Gateway using Sprign Cloud Gateway

Getting JWT from SecurityManager using API Gateway

**CURL Command:**

`curl --location --request POST 'http://localhost:9999/securitymanager/oauth/token' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--header 'Authorization: Basic Y2xpZW50OnNlY3JldA==' \
--header 'Cookie: JSESSIONID=9E41DC0312213DC0467B61E45FEC5E67' \
--data-urlencode 'username=admin@TEST01.com' \
--data-urlencode 'password=password' \
--data-urlencode 'grant_type=password'`
