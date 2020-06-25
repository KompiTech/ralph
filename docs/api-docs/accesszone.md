# accesszone Ralph resource endpoint description

Access zone asset represents access zone for access cards and can be nested

Resource available on `/api/access-zone/`
```
{
    "count": 2,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": 1,
            "url": "http://localhost:5555/api/access-zone/1/",
            "ui_url": "http://localhost:5555/access_cards/accesszone/1/",
            "name": "Access zone totok",
            "description": "Totok ",
            "lft": 1,
            "rght": 4,
            "tree_id": 1,
            "level": 0,
            "parent": null
        },
        {
            "id": 2,
            "url": "http://localhost:5555/api/access-zone/2/",
            "ui_url": "http://localhost:5555/access_cards/accesszone/2/",
            "name": "Access zone tamtok",
            "description": "Tamtok",
            "lft": 2,
            "rght": 3,
            "tree_id": 1,
            "level": 1,
            "parent": {
                "id": 1,
                "url": "http://localhost:5555/api/access-zone/1/",
                "ui_url": "http://localhost:5555/access_cards/accesszone/1/",
                "name": "Access zone totok",
                "description": "Totok ",
                "lft": 1,
                "rght": 4,
                "tree_id": 1,
                "level": 0,
                "parent": null
            }
        }
    ]
}
```

Detail about given resource `/api//accessories/id`
```
{
    "id": 4,
    "url": "http://localhost:5555/api/access-zone/4/",
    "ui_url": "http://localhost:5555/access_cards/accesszone/4/",
    "name": "A1",
    "description": "A1 zone description",
    "lft": 6,
    "rght": 7,
    "tree_id": 1,
    "level": 1,
    "parent": {
        "id": 1,
        "url": "http://localhost:5555/api/access-zone/1/",
        "ui_url": "http://localhost:5555/access_cards/accesszone/1/",
        "name": "Access zone totok",
        "description": "Totok ",
        "lft": 1,
        "rght": 8,
        "tree_id": 1,
        "level": 0,
        "parent": null
    }
}
```

Create asset payload:
```
{
    "parent": 1,
    "name": "A1",
    "description": "A1 zone description"
}
```

References:
```
Parent - parent access zone
```