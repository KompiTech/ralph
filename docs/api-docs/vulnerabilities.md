# vulnerabilities Ralph resource endpoint description
Vulnerabilities resource represents known and present or fixed vulnerabilities in the system.

Resource available on `/api/vulnerabilities/`

Detail about given resource `/api/vulnerabilities/id`
```
{
  "id": 1,
  "url": "http://ralph-demo.allegro.tech/api/vulnerabilities/1/",
  "tags": [
    "execute",
    "code",
    "hack"
  ],
  "ui_url": "http://ralph-demo.allegro.tech/security/vulnerability/1/",
  "created": "2019-08-02T14:21:44.975090",
  "modified": "2020-06-17T13:18:59.619547",
  "name": "PHP: CVE-2019-9641",
  "display_name": "CVE-2019-9641",
  "patch_deadline": null,
  "risk": "high",
  "external_vulnerability_id": 1234
}

```
