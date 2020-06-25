# Ralph API documentation

Ralph API is accessible on url `https://<YOUR-RALPH-URL>/api/<RESOURCE-NAME>/`.
This url will list all items of the given resource.
If you want to retrieve specific item you need to know item id.
The specific item can be retrieved on `https://<YOUR-RALPH-URL>/api/<RESOURCE-NAME>/<RESOURCE-ID>/`

Resources can be queried via curl tool:
```
curl -X GET https://ralph-demo.allegro.tech/api/regions/12/ -H 'Authorization: Token fc666ba738bb98525da9c04eba6987420f2f5044'
```

For example:
```
curl -X GET https://ralph-demo.allegro.tech/api/regions/12/ -H 'Authorization: Token fc666ba738bb98525da9c04eba6987420f2f5044'
```

You can limit number of returned objects:
```
curl -X GET https://ralph-demo.allegro.tech/api/regions/12/?limit=5 -H 'Authorization: Token fc666ba738bb98525da9c04eba6987420f2f5044'
```

For resources creation use curl:
```
curl -X POST https://ralph-demo.allegro.tech/api/users/ -H 'Authorization: Token fc666ba738bb98525da9c04eba6987420f2f5044' \
-H 'Accept: application/json' \
-H 'Content-Type: application/json' \
--data-raw '{"param": "value"}'
```

For resource creation with its relations use id of the referenced asset to add the relation. Here we create user with Name Jon Doe and we reference region with id 100. Then we also connect user with assets he use, in this example 1000 can be id of his laptop and 1001 can be his work phone.
```
{
  "name": "Jon Doe",
  "region": 100,
  "assets_as_user": [1000, 1001]
}
```

## Available resources

- [accesscard](accesscard.md)
- [accessories](accessories.md)
- [accesszone](accesszone.md)
- [articles](articles.md)
- [assetholders](assetholders.md)
- [assetmodels](assetmodels.md)
- [backofficeassets](backofficeassets.md)
- [bars](bars.md)
- [baseobjectclusters](baseobjectclusters.md)
- [baseobjects](baseobjects.md)
- [baseobjectslicences](baseobjectslicences.md)
- [baseobjectssupports](baseobjectssupports.md)
- [budgetinfo](budgetinfo.md)
- [businesssegments](businesssegments.md)
- [cars](cars.md)
- [categories](categories.md)
- [cloudflavors](cloudflavors.md)
- [cloudhosts](cloudhosts.md)
- [cloudimages](cloudimages.md)
- [cloudprojects](cloudprojects.md)
- [cloudproviders](cloudproviders.md)
- [clusters](clusters.md)
- [clustertypes](clustertypes.md)
- [configurationclasses](configurationclasses.md)
- [configurationmodules](configurationmodules.md)
- [customfields](customfields.md)
- [databases](databases.md)
- [datacenterassets](datacenterassets.md)
- [datacenters](datacenters.md)
- [dchosts](dchosts.md)
- [disks](disks.md)
- [dnsprovider](dnsprovider.md)
- [dnsservergroup](dnsservergroup.md)
- [dnsservers](dnsservers.md)
- [domaincategory](domaincategory.md)
- [domains](domains.md)
- [environments](environments.md)
- [ethernets](ethernets.md)
- [fibrechannelcards](fibrechannelcards.md)
- [foo](foo.md)
- [foos](foos.md)
- [graph](graph.md)
- [groups](groups.md)
- [ipaddresses](ipaddresses.md)
- [library](library.md)
- [licences](licences.md)
- [licencetypes](licencetypes.md)
- [licenceusers](licenceusers.md)
- [longarticles](longarticles.md)
- [manufacturerkind](manufacturerkind.md)
- [manufacturers](manufacturers.md)
- [manufacturers](manufacturers.md)
- [memory](memory.md)
- [networkenvironments](networkenvironments.md)
- [networkkinds](networkkinds.md)
- [networks](networks.md)
- [officeinfrastructures](officeinfrastructures.md)
- [operation](operation.md)
- [operationstatus](operationstatus.md)
- [operationtype](operationtype.md)
- [processors](processors.md)
- [profitcenters](profitcenters.md)
- [rackaccessories](rackaccessories.md)
- [racks](racks.md)
- [regions](regions.md)
- [scminfo](scminfo.md)
- [securityscans](securityscans.md)
- [serverrooms](serverrooms.md)
- [services](services.md)
- [servicesenvironments](servicesenvironments.md)
- [simcard](simcard.md)
- [simcardcellularcarrier](simcardcellularcarrier.md)
- [simcardfeature](simcardfeature.md)
- [software](software.md)
- [somemodel](somemodel.md)
- [sslcertificates](sslcertificates.md)
- [supports](supports.md)
- [supporttypes](supporttypes.md)
- [teams](teams.md)
- [transitions](transitions.md)
- [transitionsaction](transitionsaction.md)
- [transitionsjob](transitionsjob.md)
- [transitionsmodel](transitionsmodel.md)
- [users](users.md)
- [vips](vips.md)
- [virtualservers](virtualservers.md)
- [virtualservertypes](virtualservertypes.md)
- [vulnerabilities](vulnerabilities.md)
- [warehouses](warehouses.md)
