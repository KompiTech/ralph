# supports Ralph resource endpoint description
Information about available supports for company, in different regions

### Relations
Support have relation to support type (24x7, linux etc.) and region in which this support is available.

Resource available on `/api/supports/`

Detail about given reseource `/api/supports/id`
```
{
  "id": 1414,
  "url": "http://ralph-demo.allegro.tech/api/supports/1414/",
  "object_type": "support",
  "__str__": "support: Windows Tecnical Support (2020-06-09)",
  "base_objects": [],
  "service_env": null,
  "tags": [],
  "ui_url": "http://ralph-demo.allegro.tech/supports/support/1414/",
  "created": "2020-02-17T14:27:11.918425",
  "modified": "2020-06-08T17:28:11.325796",
  "remarks": "",
  "name": "Windows Tecnical Support",
  "asset_type": "all",
  "contract_id": "contrato2",
  "description": "Microsoft Support",
  "price": "0.00",
  "date_from": "2020-02-16",
  "date_to": "2020-06-09",
  "escalation_path": "",
  "contract_terms": "",
  "sla_type": "",
  "status": "new",
  "producer": "Microsoft",
  "supplier": "",
  "serial_no": "",
  "invoice_no": "",
  "invoice_date": null,
  "period_in_months": null,
  "parent": null,
  "region": {
    "id": 6,
    "url": "http://ralph-demo.allegro.tech/api/regions/6/",
    "ui_url": "http://ralph-demo.allegro.tech/accounts/region/6/",
    "name": "Mid-West",
    "country": "Albania",
    "stocktaking_enabled": true
  },
  "property_of": null,
  "budget_info": null,
  "support_type": {
    "id": 18,
    "url": "http://ralph-demo.allegro.tech/api/support-types/18/",
    "ui_url": "http://ralph-demo.allegro.tech/supports/supporttype/18/",
    "name": "Tecnical"
  }
}

```

Create support asset payload:
```
{
  "name": "OpenContrail L3 support",
  "asset_type": "data center",
  "contract_id": "oc3.2",
  "description": "Support for OpenContrail network solution",
  "price": "250.00",
  "date_from": "2017-01-01",
  "date_to": "2019-12-31",
  "escalation_path": "L1 - L2 - L3",
  "sla_type": "contract specific",
  "status": "new",
  "producer": "Mirantis",
  "supplier": "OpenContrail team",
  "period_in_months": 36,
  "region": 86,
  "support_type": 11
}
```
region param is reference to specific region with given id
support_type param is reference to specific support type with given id
