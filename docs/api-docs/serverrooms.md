# serverrooms Ralph resource endpoint description
Server rooms represents individual rooms inside data center.

### Relations
Server rooms has relation to datacenter to which this room belongs to.

Resource available on `/api/server-rooms/`
```
{
  "count": 27,
  "next": "http://ralph-demo.allegro.tech/api/server-rooms/?limit=2&offset=2",
  "previous": null,
  "results": [
    {
      "id": 183,
      "url": "http://ralph-demo.allegro.tech/api/server-rooms/183/",
      "ui_url": "http://ralph-demo.allegro.tech/data_center/serverroom/183/",
      "name": "bar",
      "visualization_cols_num": 20,
      "visualization_rows_num": 20,
      "data_center": {
        "id": 195,
        "url": "http://ralph-demo.allegro.tech/api/data-centers/195/",
        "ui_url": "http://ralph-demo.allegro.tech/data_center/datacenter/195/",
        "name": "foo",
        "show_on_dashboard": true
      }
    },
    {
      "id": 188,
      "url": "http://ralph-demo.allegro.tech/api/server-rooms/188/",
      "ui_url": "http://ralph-demo.allegro.tech/data_center/serverroom/188/",
      "name": "Big Commutator",
      "visualization_cols_num": 20,
      "visualization_rows_num": 20,
      "data_center": {
        "id": 190,
        "url": "http://ralph-demo.allegro.tech/api/data-centers/190/",
        "ui_url": "http://ralph-demo.allegro.tech/data_center/datacenter/190/",
        "name": "Big Commutator",
        "show_on_dashboard": true
      }
    }
  ]
}
```

Detail about given resource `/api/server-rooms/id`
```
{
  "id": 194,
  "url": "http://ralph-demo.allegro.tech/api/server-rooms/194/",
  "ui_url": "http://ralph-demo.allegro.tech/data_center/serverroom/194/",
  "name": "Room 1A",
  "visualization_cols_num": 5,
  "visualization_rows_num": 20,
  "data_center": {
    "id": 193,
    "url": "http://ralph-demo.allegro.tech/api/data-centers/193/",
    "ui_url": "http://ralph-demo.allegro.tech/data_center/datacenter/193/",
    "name": "EU",
    "show_on_dashboard": true
  }
}
```

Create server room asset payload:
```
{
  "name": "Room 1A",
  "visualization_cols_num": 5,
  "data_center": 193
}
```
Data center param refers to data center asset with id 193.
