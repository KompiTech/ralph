# networks Ralph resource endpoint description
Network resource

### Relations
Network has relation to gateway (point to ip address), next has connection to dns servers for the network or to service environment.

Resource available on `/api/networks/`

Detail about given network `/api/networks/id`
```
{
  "id": 88,
  "url": "http://ralph-demo.allegro.tech/api/networks/88/",
  "ui_url": "http://ralph-demo.allegro.tech/networks/network/88/",
  "name": "Office Network",
  "created": "2020-02-03T15:15:20.989829",
  "modified": "2020-05-04T13:25:29.307550",
  "address": "192.168.48.0/23",
  "remarks": "",
  "vlan": 1010,
  "min_ip": "3232247808",
  "max_ip": "3232248319",
  "dhcp_broadcast": true,
  "reserved_from_beginning": 10,
  "reserved_from_end": 0,
  "lft": 1,
  "rght": 4,
  "tree_id": 3,
  "level": 0,
  "parent": null,
  "gateway": {
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
  },
  "network_environment": null,
  "kind": null,
  "service_env": {
    "id": 1372,
    "url": "http://ralph-demo.allegro.tech/api/services-environments/1372/",
    "tags": [],
    "ui_url": "http://ralph-demo.allegro.tech/assets/serviceenvironment/1372/",
    "created": "2020-02-05T10:01:42.356048",
    "modified": "2020-02-05T10:01:42.356073",
    "remarks": "",
    "parent": null,
    "service_env": null,
    "configuration_path": null,
    "service": "http://ralph-demo.allegro.tech/api/services/42/",
    "environment": "http://ralph-demo.allegro.tech/api/environments/32/"
  },
  "dns_servers_group": null,
  "terminators": [],
  "racks": []
}
```
