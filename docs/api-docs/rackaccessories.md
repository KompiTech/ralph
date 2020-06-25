# rackaccessories Ralph resource endpoint description
Rack accessories represents for example generic 1U server or specific 2U HPE ProLiant DL560 server. Basically everting what can be mounted into rack.

### Relations
Rack accessory resource has relation to rack in which is mounted.

Resource available on `/api/rack-accessories/`

Detail about given rack accessory `/api/rack-accessories/id/`
```
{
  "id": 443,
  "url": "http://ralph-demo.allegro.tech/api/rack-accessories/443/",
  "name": "2+U+HP+server",
  "ui_url": "http://ralph-demo.allegro.tech/data_center/rackaccessory/443/",
  "orientation": "front",
  "position": 1,
  "remarks": "",
  "accessory": "http://ralph-demo.allegro.tech/api/accessories/70/",
  "rack": "http://ralph-demo.allegro.tech/api/racks/245/"
}
```
