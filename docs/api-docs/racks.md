# racks Ralph resource endpoint description
Rack resource represents rack in dc.

### Relations
Rack has relation to one or more rack accessories and to server room in which is situated.

Resource available on `/api/racks/`

Detailed info abou given rack `/api/racks/id`
```
{
  "id": 217,
  "url": "http://ralph-demo.allegro.tech/api/racks/217/",
  "accessories": [
    {
      "id": 412,
      "url": "http://ralph-demo.allegro.tech/api/rack-accessories/412/",
      "name": "Cisco+switch",
      "ui_url": "http://ralph-demo.allegro.tech/data_center/rackaccessory/412/",
      "orientation": "front",
      "position": 2,
      "remarks": "x",
      "accessory": "http://ralph-demo.allegro.tech/api/accessories/66/",
      "rack": "http://ralph-demo.allegro.tech/api/racks/217/"
    },
    {
      "id": 413,
      "url": "http://ralph-demo.allegro.tech/api/rack-accessories/413/",
      "name": "2+U+HP+Server+%284%29",
      "ui_url": "http://ralph-demo.allegro.tech/data_center/rackaccessory/413/",
      "orientation": "front",
      "position": 6,
      "remarks": "",
      "accessory": "http://ralph-demo.allegro.tech/api/accessories/79/",
      "rack": "http://ralph-demo.allegro.tech/api/racks/217/"
    },
    {
      "id": 414,
      "url": "http://ralph-demo.allegro.tech/api/rack-accessories/414/",
      "name": "CoreSwitch-Cisco_9300-02",
      "ui_url": "http://ralph-demo.allegro.tech/data_center/rackaccessory/414/",
      "orientation": "front",
      "position": 10,
      "remarks": "",
      "accessory": "http://ralph-demo.allegro.tech/api/accessories/102/",
      "rack": "http://ralph-demo.allegro.tech/api/racks/217/"
    }
  ],
  "ui_url": "http://ralph-demo.allegro.tech/data_center/rack/217/",
  "name": "aaa",
  "description": "asas",
  "orientation": "top",
  "max_u_height": 45,
  "visualization_col": 0,
  "visualization_row": 0,
  "require_position": true,
  "reverse_ordering": true,
  "server_room": {
    "id": 164,
    "url": "http://ralph-demo.allegro.tech/api/server-rooms/164/",
    "ui_url": "http://ralph-demo.allegro.tech/data_center/serverroom/164/",
    "name": "sss",
    "visualization_cols_num": 20,
    "visualization_rows_num": 20,
    "data_center": {
      "id": 180,
      "url": "http://ralph-demo.allegro.tech/api/data-centers/180/",
      "ui_url": "http://ralph-demo.allegro.tech/data_center/datacenter/180/",
      "name": "prueba1",
      "show_on_dashboard": true
    }
  }
}
```
