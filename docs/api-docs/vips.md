# vips Ralph resource endpoint description
Virtual Ips resource

### Relations
VIPs resource have relation to service env object, to existing ip address and network.

Resource available on `/api/vips/`

Detail about given resource `/api/vips/id`
```
{
  "id": 1589,
  "url": "http://ralph-demo.allegro.tech/api/vips/1589/",
  "object_type": "vip",
  "custom_fields": {},
  "configuration_variables": {},
  "__str__": "VIP: IP: 10.0.11.221, port: 0, protocol: TCP",
  "tags": [],
  "service_env": {
    "id": 1631,
    "service": "OS",
    "environment": "Linux",
    "url": "http://ralph-demo.allegro.tech/api/services-environments/1631/",
    "service_uid": null,
    "ui_url": "http://ralph-demo.allegro.tech/assets/serviceenvironment/1631/"
  },
  "licences": [],
  "configuration_path": null,
  "ui_url": "http://ralph-demo.allegro.tech/data_center/vip/1589/",
  "created": "2020-05-06T18:22:36.651297",
  "modified": "2020-06-08T08:54:20.595101",
  "remarks": "",
  "name": "test",
  "port": 0,
  "protocol": "TCP",
  "parent": null,
  "ip": {
    "id": 206,
    "url": "http://ralph-demo.allegro.tech/api/ipaddresses/206/",
    "ui_url": "http://ralph-demo.allegro.tech/networks/ipaddress/206/",
    "created": "2020-04-13T11:21:50.979340",
    "modified": "2020-05-21T16:40:12.414169",
    "last_seen": "2020-04-13T11:21:50.979380",
    "address": "10.0.11.221",
    "hostname": null,
    "number": "167775197",
    "is_management": false,
    "is_public": false,
    "is_gateway": true,
    "status": "reserved",
    "dhcp_expose": false,
    "ethernet": null,
    "network": "http://ralph-demo.allegro.tech/api/networks/107/"
  }
}
```
