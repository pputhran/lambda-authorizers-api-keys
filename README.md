# lambda-authorizers-api-keys
Example of API Gateway configured with Lambda authorizer and API Key

### Invoke the API 
curl --location --request GET 'HTTP_URL' \
--header 'Authorization: allow' \
--header 'x-api-key: <API_KEY>'
