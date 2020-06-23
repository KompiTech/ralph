# regions Ralph resource endpoint description
Region represents branch region in some country.

Resource available on `/api/regions/`
```
{
  "count": 82,
  "next": "http://ralph-demo.allegro.tech/api/regions/?limit=3&offset=3",
  "previous": null,
  "results": [
    {
      "id": 1,
      "url": "http://ralph-demo.allegro.tech/api/regions/1/",
      "ui_url": "http://ralph-demo.allegro.tech/accounts/region/1/",
      "name": "gggpl",
      "country": "Albania",
      "stocktaking_enabled": true
    },
    {
      "id": 2,
      "url": "http://ralph-demo.allegro.tech/api/regions/2/",
      "ui_url": "http://ralph-demo.allegro.tech/accounts/region/2/",
      "name": "de",
      "country": "Germany",
      "stocktaking_enabled": true
    },
    {
      "id": 3,
      "url": "http://ralph-demo.allegro.tech/api/regions/3/",
      "ui_url": "http://ralph-demo.allegro.tech/accounts/region/3/",
      "name": "ua",
      "country": "Albania",
      "stocktaking_enabled": true
    }
  ]
}

```

Detail about given resource `/api/regions/id`
```
{
  "id": 86,
  "url": "http://ralph-demo.allegro.tech/api/regions/86/",
  "ui_url": "http://ralph-demo.allegro.tech/accounts/region/86/",
  "name": "CZE",
  "country": "Czech Republic",
  "stocktaking_enabled": true
}
```

Create regions asset payload:
```
{
  "name": "czechia",
  "country": "Czech Republic",
  "stocktaking_enabled": true
}
```
