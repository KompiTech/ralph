# supporttypes Ralph resource endpoint description
Represents support type (24x7, 5x8, technical, Cisco etc.)

Resource available on `/api/support-types/`
```
{
  "count": 21,
  "next": "http://ralph-demo.allegro.tech/api/support-types/?limit=3&offset=3",
  "previous": null,
  "results": [
    {
      "id": 10,
      "url": "http://ralph-demo.allegro.tech/api/support-types/10/",
      "ui_url": "http://ralph-demo.allegro.tech/supports/supporttype/10/",
      "name": "345678"
    },
    {
      "id": 11,
      "url": "http://ralph-demo.allegro.tech/api/support-types/11/",
      "ui_url": "http://ralph-demo.allegro.tech/supports/supporttype/11/",
      "name": "7x24"
    },
    {
      "id": 2,
      "url": "http://ralph-demo.allegro.tech/api/support-types/2/",
      "ui_url": "http://ralph-demo.allegro.tech/supports/supporttype/2/",
      "name": "additional"
    }
  ]
}
```

Detail about given resource `/api/support-types/id`
```
{
  "id": 1,
  "url": "http://ralph-demo.allegro.tech/api/support-types/1/",
  "ui_url": "http://ralph-demo.allegro.tech/supports/supporttype/1/",
  "name": "warranty"
}
```

Create support type asset payload:
```
{
  "name": "OpenContrail L3 support"
}
```
