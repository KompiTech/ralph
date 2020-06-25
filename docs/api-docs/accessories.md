# accessories Ralph resource endpoint description


Accessory asset represents accessory assigned to rack accessory

Resource available on `/api/accessories/`
```
{
    "count": 122,
    "next": "http://ralph-demo.allegro.tech/api/accessories/?limit=10&offset=10",
    "previous": null,
    "results": [
        {
            "id": 86,
            "url": "http://ralph-demo.allegro.tech/api/accessories/86/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/86/",
            "name": "1+U+HP+Server+%286%29"
        },
        {
            "id": 80,
            "url": "http://ralph-demo.allegro.tech/api/accessories/80/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/80/",
            "name": "1+U+HP+Server+1"
        },
        {
            "id": 81,
            "url": "http://ralph-demo.allegro.tech/api/accessories/81/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/81/",
            "name": "1+U+HP+Server+2"
        },
        {
            "id": 82,
            "url": "http://ralph-demo.allegro.tech/api/accessories/82/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/82/",
            "name": "1+U+HP+Server+3"
        },
        {
            "id": 83,
            "url": "http://ralph-demo.allegro.tech/api/accessories/83/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/83/",
            "name": "1+U+HP+Server+4"
        },
        {
            "id": 84,
            "url": "http://ralph-demo.allegro.tech/api/accessories/84/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/84/",
            "name": "1+U+HP+Server+5"
        },
        {
            "id": 85,
            "url": "http://ralph-demo.allegro.tech/api/accessories/85/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/85/",
            "name": "1+U+HP+Server+6"
        },
        {
            "id": 87,
            "url": "http://ralph-demo.allegro.tech/api/accessories/87/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/87/",
            "name": "1+U+HP+Server+7"
        },
        {
            "id": 88,
            "url": "http://ralph-demo.allegro.tech/api/accessories/88/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/88/",
            "name": "1+U+HP+Server+8"
        },
        {
            "id": 92,
            "url": "http://ralph-demo.allegro.tech/api/accessories/92/",
            "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/92/",
            "name": "12"
        }
    ]
}
```

Detail about given resource `/api//accessories/id`
```
{
    "id": 92,
    "url": "http://ralph-demo.allegro.tech/api/accessories/92/",
    "ui_url": "http://ralph-demo.allegro.tech/data_center/accessory/92/",
    "name": "Pen"
}
```

Create asset payload:
```
{
  "name": "Pen"
}
```