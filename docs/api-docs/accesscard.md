# accesscard Ralph resource endpoint description

Access card asset represents 

Resource available on `/api/access-card/`
```
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": 1,
            "status": "new",
            "user": {
                "id": 1,
                "url": "http://localhost:5555/api/users/1/",
                "username": "ralph",
                "first_name": "",
                "last_name": "",
                "email": "",
                "country": "Poland",
                "ui_url": "http://localhost:5555/accounts/ralphuser/1/"
            },
            "owner": {
                "id": 1,
                "url": "http://localhost:5555/api/users/1/",
                "username": "ralph",
                "first_name": "",
                "last_name": "",
                "email": "",
                "country": "Poland",
                "ui_url": "http://localhost:5555/accounts/ralphuser/1/"
            },
            "created": "2020-06-25T14:29:27.505142",
            "modified": "2020-06-25T14:29:27.505165",
            "visual_number": "1231223123",
            "system_number": "123123123",
            "issue_date": "2020-06-25",
            "notes": "fsdfsdf",
            "region": {
                "id": 1,
                "url": "http://localhost:5555/api/regions/1/",
                "ui_url": "http://localhost:5555/accounts/region/1/",
                "name": "Region 1",
                "country": "Bahamas",
                "stocktaking_enabled": false
            },
            "access_zones": [
                {
                    "id": 1,
                    "name": "Access zone totok",
                    "parent": null,
                    "description": "Totok ",
                    "ui_url": "http://localhost:5555/access_cards/accesszone/1/"
                }
            ],
            "ui_url": "http://localhost:5555/access_cards/accesscard/1/"
        }
    ]
}
```

Detail about given resource `/api/access-card/id`
```
{
    "id": 1,
    "status": "new",
    "user": {
        "id": 1,
        "url": "http://localhost:5555/api/users/1/",
        "username": "ralph",
        "first_name": "",
        "last_name": "",
        "email": "",
        "country": "Poland",
        "ui_url": "http://localhost:5555/accounts/ralphuser/1/"
    },
    "owner": {
        "id": 1,
        "url": "http://localhost:5555/api/users/1/",
        "username": "ralph",
        "first_name": "",
        "last_name": "",
        "email": "",
        "country": "Poland",
        "ui_url": "http://localhost:5555/accounts/ralphuser/1/"
    },
    "created": "2020-06-25T14:29:27.505142",
    "modified": "2020-06-25T14:29:27.505165",
    "visual_number": "1231223123",
    "system_number": "123123123",
    "issue_date": "2020-06-25",
    "notes": "fsdfsdf",
    "region": {
        "id": 1,
        "url": "http://localhost:5555/api/regions/1/",
        "ui_url": "http://localhost:5555/accounts/region/1/",
        "name": "Region 1",
        "country": "Bahamas",
        "stocktaking_enabled": false
    },
    "access_zones": [
        {
            "id": 1,
            "name": "Access zone totok",
            "parent": null,
            "description": "Totok ",
            "ui_url": "http://localhost:5555/access_cards/accesszone/1/"
        }
    ],
    "ui_url": "http://localhost:5555/access_cards/accesscard/1/"
}
```

Create access card asset payload:
```
{
    "visual_number": "1111",
    "system_number": "3333",
    "status": 2,
    "region": 1,
    "issue_date": "2020-06-25",
    "notes": "Note",
    "user": 1,
    "owner": 1,
    "access_zones": [1]
}
```

References:
```
user
owner
access_zones
region
```
