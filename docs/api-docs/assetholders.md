# assetholders Ralph resource endpoint description

<!-- TODO Add better definition -->
Asset holder asset represents asset holder 

Resource available on `/api/assetholders/`
```
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": 1,
            "url": "http://localhost:5555/api/assetholders/1/",
            "ui_url": "http://localhost:5555/assets/assetholder/1/",
            "name": "asset_holding",
            "created": "2020-06-25T15:30:39.454553",
            "modified": "2020-06-25T15:30:39.454576"
        }
    ]
}
```

Detail about given resource `/api//accessories/id`
```
{
    "id": 1,
    "url": "http://localhost:5555/api/assetholders/1/",
    "ui_url": "http://localhost:5555/assets/assetholder/1/",
    "name": "asset_holding",
    "created": "2020-06-25T15:30:39.454553",
    "modified": "2020-06-25T15:30:39.454576"
}
```

Create asset payload:
```
{
    "name": "Asset hodling 2"
}
```

References:
```
```