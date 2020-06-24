# transitions Ralph resource endpoint description
Transition resource definition

### Relations
Transitions resource has relation to transition model and to one or more transition actions.

Resource available on `/api/transitions/`

Detail about given resource `/api/transitions/`
```
{
  "id": 13,
  "url": "http://ralph-demo.allegro.tech/api/transitions/13/",
  "source": [
    "new",
    "in use",
    "to deploy",
    "liquidated"
  ],
  "target": "new",
  "name": "Peter+Winter",
  "run_asynchronously": true,
  "async_service_name": "ASYNC_TRANSITIONS",
  "template_name": "",
  "success_url": "555-555-0199@example.com",
  "model": "http://ralph-demo.allegro.tech/api/transitions-model/4/",
  "actions": [
    "http://ralph-demo.allegro.tech/api/transitions-action/28/"
  ]
}
```

