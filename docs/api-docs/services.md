# services Ralph resource endpoint description
Service which is used in the company (for example k8s, Firewall, LDAP)

### Relations
Service has relation to environment (for example AWS, infra, staggin, production etc.)

Resource available `/api/services/`

Detail about given resource `/api/services/id`
```
{
  "id": 6,
  "url": "http://ralph-demo.allegro.tech/api/services/6/",
  "business_owners": [],
  "technical_owners": [],
  "ui_url": "http://ralph-demo.allegro.tech/assets/service/6/",
  "name": "Kubernetes",
  "created": "2019-02-19T10:34:05.882588",
  "modified": "2020-04-16T21:58:30.154426",
  "active": true,
  "uid": null,
  "cost_center": "",
  "profit_center": null,
  "business_segment": null,
  "support_team": null,
  "environments": [
    {
      "id": 7,
      "url": "http://ralph-demo.allegro.tech/api/environments/7/",
      "ui_url": "http://ralph-demo.allegro.tech/assets/environment/7/",
      "name": "PRD",
      "created": "2019-02-19T10:33:08.554350",
      "modified": "2020-04-16T21:58:20.670384"
    }
  ]
}
```
