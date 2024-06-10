For all example relays, we will use the following JSON example structure for an ingested message:

```json5
{
  "key": 101,
  "value": {
    "siteId": 101,
    "country": "USA",
    "timestamp": 1660235884,
    "status": {
      "alerts": 2,
      "capacity": 500,
      "stock": 200
    },
    "vehicles": [
      { "id": "v1", "lat": 51.5, "long": 0.5 },
      { "id": "v2", "lat": 51.3, "long": 0.6 }
    ]
  }
}
```