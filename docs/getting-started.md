# Getting Started

This guide helps you start using the DocManaga API.

## Authentication

All API requests require an API key.

Example header:

Authorization: Bearer YOUR_API_KEY

## Base URL

https://api.docmanaga.com/v1

## First Request

```bash
curl -X GET https://api.docmanaga.com/v1/documents \
	-H "Authorization: Bearer YOUR_API_KEY"
```
