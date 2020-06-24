# users Ralph resource endpoint description
Resource which represents users in the system and information about them

### Relations
User has relation to licences related to him/her aka `Assigned licences`. Then has relation to assets which owns or is user of these assets aka `Assigned assets`. User also has relation to team if is part of some. User can also have relation to one or more regions.

Resource available on `/api/users/`

Detail about given resource `/api/users/id`
```
{
  "id": 10113,
  "url": "http://ralph-demo.allegro.tech/api/users/10113/",
  "assets_as_user": [],
  "assets_as_owner": [],
  "licences": [
    {
      "id": 120,
      "url": "http://ralph-demo.allegro.tech/api/licence-users/120/",
      "licence": {
        "id": 1628,
        "url": "http://ralph-demo.allegro.tech/api/licences/1628/",
        "ui_url": "http://ralph-demo.allegro.tech/licences/licence/1628/",
        "created": "2020-05-26T05:55:39.975157",
        "modified": "2020-05-26T05:56:37.562219",
        "remarks": "",
        "number_bought": 100,
        "sn": "",
        "niw": "1251452",
        "invoice_date": null,
        "valid_thru": null,
        "order_no": "",
        "price": "0.00",
        "depreciation_rate": "50.00",
        "accounting_id": "",
        "provider": "",
        "invoice_no": "",
        "license_details": "",
        "region": {
          "id": 69,
          "url": "http://ralph-demo.allegro.tech/api/regions/69/",
          "ui_url": "http://ralph-demo.allegro.tech/accounts/region/69/",
          "name": "Cairo",
          "country": "Egypt",
          "stocktaking_enabled": false
        },
        "manufacturer": {
          "id": 19,
          "url": "http://ralph-demo.allegro.tech/api/manufacturers/19/",
          "ui_url": "http://ralph-demo.allegro.tech/assets/manufacturer/19/",
          "name": "Microsoft",
          "created": "2019-02-25T21:15:20",
          "modified": "2020-04-27T08:25:51.807160",
          "manufacturer_kind": "http://ralph-demo.allegro.tech/api/manufacturer-kind/10/"
        },
        "licence_type": {
          "id": 40,
          "url": "http://ralph-demo.allegro.tech/api/licence-types/40/",
          "ui_url": "http://ralph-demo.allegro.tech/licences/licencetype/40/",
          "name": "Concurrent User"
        },
        "property_of": null,
        "software": {
          "id": 67,
          "url": "http://ralph-demo.allegro.tech/api/software/67/",
          "ui_url": "http://ralph-demo.allegro.tech/licences/software/67/",
          "name": "Office 365 E5 ",
          "asset_type": "part"
        },
        "office_infrastructure": null,
        "budget_info": null
      },
      "quantity": 1,
      "user": "http://ralph-demo.allegro.tech/api/users/10113/"
    }
  ],
  "ui_url": "http://ralph-demo.allegro.tech/accounts/ralphuser/10113/",
  "last_login": null,
  "is_superuser": false,
  "username": "michael.jordan",
  "first_name": "Michael",
  "last_name": "Jordan",
  "email": "michael.jordan@chicago-bulls.com",
  "is_staff": false,
  "is_active": true,
  "date_joined": "2020-03-29T11:35:07",
  "country": "Honduras",
  "city": "",
  "company": "Chicago Bulls",
  "employee_id": "",
  "profit_center": "",
  "cost_center": "",
  "department": "NBA players",
  "manager": "Coach",
  "location": "Chicaho",
  "segment": "",
  "team": {
    "id": 15,
    "url": "http://ralph-demo.allegro.tech/api/teams/15/",
    "ui_url": "http://ralph-demo.allegro.tech/accounts/team/15/",
    "name": "Bulls"
  },
  "regions": []
}
```

Create user asset payload:
```
{
  "assets_as_user": [
    1639
  ],
  "assets_as_owner": [],
  "licenses": [
    1644,
    1674,
    1593
  ],
  "is_supersuser": false,
  "username": "karel.vomacka",
  "first_name": "Karel",
  "last_name": "Vomacka",
  "email": "karel.vomacka@seznam.cz",
  "is_staff": false,
  "is_active": true,
  "date_joined": "2020-06-24T15:00:30",
  "country": "Czech Republic",
  "city": "Prague",
  "company": "IBM",
  "department": "Help Desk and IT support",
  "team": 15,
  "regions": [
    86
  ]
}
```
 Return error `{"detail":"Method \"POST\" not allowed."}`
