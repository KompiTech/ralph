# teams Ralph resource endpoint description
Teams reseource groups users

Resource available on `/api/teams/`
```
{
  "count": 14,
  "next": "http://ralph-demo.allegro.tech/api/teams/?limit=3&offset=3",
  "previous": null,
  "results": [
    {
      "id": 7,
      "url": "http://ralph-demo.allegro.tech/api/teams/7/",
      "ui_url": "http://ralph-demo.allegro.tech/accounts/team/7/",
      "name": "ana"
    },
    {
      "id": 3,
      "url": "http://ralph-demo.allegro.tech/api/teams/3/",
      "ui_url": "http://ralph-demo.allegro.tech/accounts/team/3/",
      "name": "apos"
    },
    {
      "id": 8,
      "url": "http://ralph-demo.allegro.tech/api/teams/8/",
      "ui_url": "http://ralph-demo.allegro.tech/accounts/team/8/",
      "name": "B&E"
    }
  ]
}

```

Detail about given resource `/api/teams/id`
```
{
  "id": 2,
  "url": "http://ralph-demo.allegro.tech/api/teams/2/",
  "ui_url": "http://ralph-demo.allegro.tech/accounts/team/2/",
  "name": "test"
}

```
