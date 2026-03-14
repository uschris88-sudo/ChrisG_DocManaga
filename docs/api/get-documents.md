# Get All Documents

Returns a list of all documents stored in the account.

## Endpoint

GET /documents

## Request Example

```bash
curl -X GET https://api.docmanaga.com/v1/documents \
	-H "Authorization: Bearer YOUR_API_KEY"
```

## Response Example

```json
{
	"documents": [
		{
			"id": "doc_001",
			"name": "invoice.pdf",
			"size": "1.2MB",
			"created_at": "2026-01-10"
		}
	]
}
```
