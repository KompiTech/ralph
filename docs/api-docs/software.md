# software Ralph resource endpoint description
Software asset represents software running on the machines etc.

Resource available on `/api/software/`
```
{
  "count": 55,
  "next": "http://ralph-demo.allegro.tech/api/software/?limit=3&offset=3",
  "previous": null,
  "results": [
    {
      "id": 66,
      "url": "http://ralph-demo.allegro.tech/api/software/66/",
      "ui_url": "http://ralph-demo.allegro.tech/licences/software/66/",
      "name": "Office 365 E5 [EA]",
      "asset_type": "all"
    },
    {
      "id": 67,
      "url": "http://ralph-demo.allegro.tech/api/software/67/",
      "ui_url": "http://ralph-demo.allegro.tech/licences/software/67/",
      "name": "Office 365 E5 ",
      "asset_type": "part"
    },
    {
      "id": 68,
      "url": "http://ralph-demo.allegro.tech/api/software/68/",
      "ui_url": "http://ralph-demo.allegro.tech/licences/software/68/",
      "name": "Project Professional",
      "asset_type": "all"
    }
  ]
}
```

Detail about given resource `/api/software/id`
```
{
  "id": 80,
  "url": "http://ralph-demo.allegro.tech/api/software/80/",
  "ui_url": "http://ralph-demo.allegro.tech/licences/software/80/",
  "name": "OpenVPN",
  "asset_type": "part"
}
```

Create software asset payload:
```
{
  "name": "Slack",
  "asset_type": "back office"
}
```

asset_type can be one of:
- back office
- data center
- part
- all
