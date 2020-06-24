# servicesenvironments Ralph resource endpoint description

### Relations
Service environments has relations to service and environments asset.

Resource available on `/api/servicesenvironments/`

Detail about given resource `/api/servicesenvironments/id`
```
{
  "id": 1630,
  "url": "http://ralph-demo.allegro.tech/api/services-environments/1630/",
  "object_type": "serviceenvironment",
  "custom_fields": {},
  "configuration_variables": {},
  "__str__": "service environment: OS - Windows",
  "business_owners": [],
  "technical_owners": [],
  "tags": [],
  "ui_url": "http://ralph-demo.allegro.tech/assets/serviceenvironment/1630/",
  "created": "2020-05-26T11:18:42.503581",
  "modified": "2020-06-07T17:59:32.700393",
  "remarks": "",
  "configuration_path": null,
  "service": {
    "id": 61,
    "url": "http://ralph-demo.allegro.tech/api/services/61/",
    "ui_url": "http://ralph-demo.allegro.tech/assets/service/61/",
    "name": "OS",
    "created": "2020-05-26T11:17:52.894369",
    "modified": "2020-05-26T11:17:52.894390",
    "active": true,
    "uid": null,
    "cost_center": "",
    "profit_center": null,
    "business_segment": null,
    "support_team": null,
    "environments": [
      "http://ralph-demo.allegro.tech/api/environments/49/",
      "http://ralph-demo.allegro.tech/api/environments/48/"
    ],
    "business_owners": [],
    "technical_owners": []
  },
  "environment": {
    "id": 48,
    "url": "http://ralph-demo.allegro.tech/api/environments/48/",
    "ui_url": "http://ralph-demo.allegro.tech/assets/environment/48/",
    "name": "Windows",
    "created": "2020-05-26T11:18:10.575826",
    "modified": "2020-05-26T11:18:10.575847"
  }
}

```
