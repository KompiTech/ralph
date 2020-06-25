# virtualservers Ralph resource endpoint description
Virtual server resource

### Relations
Virtual server have relation to virtual server type, hypervisor on which running (dc-asset for example linux server). Next virtual server can have relation to licenses (oracle db etc.), service env (stagging, prod, etc.), hw (processor, disk, network) and owners.

Resource available on `/api/virtual-servers/`

Detail about given resource `/api/virtual-servers/id`
```
{
  "id": 1665,
  "url": "http://ralph-demo.allegro.tech/api/virtual-servers/1665/",
  "business_owners": [],
  "technical_owners": [],
  "ethernet": [],
  "ipaddresses": [],
  "disk": [],
  "memory": [],
  "processors": [],
  "object_type": "virtualserver",
  "custom_fields": {},
  "configuration_variables": {},
  "__str__": "Virtual server (VM): VirtualServer: proxmox (None)",
  "tags": [],
  "service_env": {
    "id": 1619,
    "service": "Virtual-proxmox",
    "environment": "production",
    "url": "http://ralph-demo.allegro.tech/api/services-environments/1619/",
    "service_uid": null,
    "ui_url": "http://ralph-demo.allegro.tech/assets/serviceenvironment/1619/"
  },
  "licences": [],
  "configuration_path": null,
  "type": {
    "id": 17,
    "url": "http://ralph-demo.allegro.tech/api/virtual-server-types/17/",
    "ui_url": "http://ralph-demo.allegro.tech/virtual/virtualservertype/17/",
    "name": "Maquina Virtual",
    "created": "2020-02-13T15:47:27.383347",
    "modified": "2020-02-13T15:47:27.383372"
  },
  "hypervisor": {
    "url": "http://ralph-demo.allegro.tech/api/data-center-assets/1664/",
    "ui_url": "http://ralph-demo.allegro.tech/r/9/1664/"
  },
  "scmstatuscheck": null,
  "securityscan": null,
  "ui_url": "http://ralph-demo.allegro.tech/virtual/virtualserver/1665/",
  "created": "2020-06-20T08:42:06.563002",
  "modified": "2020-06-20T18:14:20.072009",
  "remarks": "",
  "status": "new",
  "hostname": "proxmox",
  "sn": null,
  "parent": "http://ralph-demo.allegro.tech/api/base-objects/1664/"
}
```
