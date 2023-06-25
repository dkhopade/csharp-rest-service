# Accelerator Log

## Options
```json
{
  "applicationName" : "CustomerProfileAPI",
  "databaseName" : "customer-database",
  "databasePostgresStorageClass" : "default",
  "databaseType" : "postgres",
  "exposeOpenAPIEndpoint" : false,
  "projectName" : "csharp-rest-service"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ engine.transformations[0].validated.delegate (Let)
┃ ┃ ┃ Debug Adding symbol compilerSafeAppName with value 'CustomerProfileAPI'
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#databaseType == 'postgres') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol databaseResourceName with value 'customer-database'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol databasePostgresStorageClassResourceName with value 'default'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug docker-compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml didn't match [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug docker-compose.yaml matched [docker-compose.yaml, **/workload.yaml, config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug docker-compose.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [postgres-database->customer-database]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[2] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml matched [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml matched [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml matched [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml matched [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml matched [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug docker-compose.yaml didn't match [config/service-operator/postgres.yaml, config/service-operator/postgres-cluster-role.yaml, config/service-operator/postgres-cluster-instance-class.yaml, config/app-operator/postgres-resource-claim.yaml, config/app-operator/postgres-resource-claim-policy.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [storage-class-standard->default, postgresdatabase->customer-database, postgres-database->customer-database, monitoring-storage-class-standard->default]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Combo, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [DATABASE.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md matched [DATABASE.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug docker-compose.yaml didn't match [DATABASE.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1].delegate.transformations[0].sources[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will replace regex '\[tap\]' with '### PostgreSQL
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info 
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info ### ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace regex '\[local\]' with '### Local PostgreSQL...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗ ┗ Debug Multiple representations for path 'DATABASE.md', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug docker-compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'appsettings.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'PostgreSqlSeeder.cs', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'RestService.csproj', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Models/CustomerProfile.cs', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload-basic.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'DATABASE.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Properties/launchSettings.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'appsettings.Development.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Models/CustomerProfilesContext.cs', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Tiltfile', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Program.cs', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Controllers/CustomerProfilesController.cs', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload-api-provider.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path '.tanzuignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj matched [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml matched [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug .tanzuignore didn't match [*.csproj, config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [*.csproj, *.sln]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj matched [*.csproj, *.sln] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug .tanzuignore didn't match [*.csproj, *.sln] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[1].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'RestService.csproj' matched 'RestService(.*)' with groups {g0=RestService.csproj, g1=.csproj} and was rewritten to 'CustomerProfileAPI.csproj'
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#exposeOpenAPIEndpoint) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (!#exposeOpenAPIEndpoint) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload-basic.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [config/workload-basic.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug .tanzuignore didn't match [config/workload-basic.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[0].sources[1].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'config/workload-basic.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=config/, filename=workload-basic.yaml, g0=config/workload-basic.yaml, g1=config/, g2=workload-basic.yaml, g3=workload-basic.yaml, g4=.yaml} and was rewritten to 'config/workload.yaml'
┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[2].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude, ReplaceText, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md, config/**, catalog/**, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug .tanzuignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/workload-basic.yaml, config/workload-api-provider.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml matched [config/workload-basic.yaml, config/workload-api-provider.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/workload-basic.yaml, config/workload-api-provider.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload-api-provider.yaml matched [config/workload-basic.yaml, config/workload-api-provider.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [csharp-rest-service->csharp-rest-service, RestService->CustomerProfileAPI]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[3].delegate.transformations[3].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*.cs]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-role.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim-policy.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/app-operator/postgres-resource-claim.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/service-operator/postgres-cluster-instance-class.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug PostgreSqlSeeder.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug RestService.csproj didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfile.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-basic.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DATABASE.md didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Models/CustomerProfilesContext.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/CustomerProfilesController.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-api-provider.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug .tanzuignore didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0].sources[4].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [RestService->CustomerProfileAPI]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/service-operator/postgres-cluster-role.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'PostgreSqlSeeder.cs', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/service-operator/postgres.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Models/CustomerProfile.cs', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Tiltfile', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Models/CustomerProfilesContext.cs', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Program.cs', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Controllers/CustomerProfilesController.cs', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/app-operator/postgres-resource-claim.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/app-operator/postgres-resource-claim-policy.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'config/service-operator/postgres-cluster-instance-class.yaml', will use the one appearing last 
┃ ┗ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[2] (Provenance)
┗ ╺ engine.transformations[1] (UniquePath)
```
