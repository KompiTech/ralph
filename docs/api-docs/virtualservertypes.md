# virtualservertypes Ralph resource endpoint description
Virtual server type define type for the virtual server asset. For example linux, wim or vmware, kvm etc.

Resource available on `/api/virtual-server-types/`
```
{
  "count": 22,
  "next": "http://ralph-demo.allegro.tech/api/virtual-server-types/?limit=3&offset=3",
  "previous": null,
  "results": [
    {
      "id": 5,
      "url": "http://ralph-demo.allegro.tech/api/virtual-server-types/5/",
      "ui_url": "http://ralph-demo.allegro.tech/virtual/virtualservertype/5/",
      "name": "1111",
      "created": "2019-02-25T13:17:14.040592",
      "modified": "2019-02-25T13:17:14.040619"
    },
    {
      "id": 19,
      "url": "http://ralph-demo.allegro.tech/api/virtual-server-types/19/",
      "ui_url": "http://ralph-demo.allegro.tech/virtual/virtualservertype/19/",
      "name": "24435",
      "created": "2020-03-11T12:57:06.552987",
      "modified": "2020-03-11T12:57:06.553008"
    },
    {
      "id": 20,
      "url": "http://ralph-demo.allegro.tech/api/virtual-server-types/20/",
      "ui_url": "http://ralph-demo.allegro.tech/virtual/virtualservertype/20/",
      "name": "AWS - BHR",
      "created": "2020-04-12T12:39:36.463600",
      "modified": "2020-04-12T12:39:36.463620"
    }
  ]
}
```

Detail about given resource `/api/virtual-server-types/id`
```
{
  "id": 9,
  "url": "http://ralph-demo.allegro.tech/api/virtual-server-types/9/",
  "ui_url": "http://ralph-demo.allegro.tech/virtual/virtualservertype/9/",
  "name": "kmv - promox ve",
  "created": "2019-04-05T13:52:01.716213",
  "modified": "2019-04-05T13:52:01.716239"
}
```
