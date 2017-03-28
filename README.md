# Behnevis-REST-API
REST API for Behnevis, written in PHP

## Required PHP modules
`php-curl`

## Required parameters:
`text`

## Example
`http://yourdomain.com/behnevis.php?text=salaam`

## Response
The API will send a response in JSON format with this objects:

`persian`: converted text from Pinglish to Persian

`error`: when parameter `text` is not set.
