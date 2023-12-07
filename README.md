| Variable      | Default Value          | Comments                   |
| ------------- |:----------------------:|:---------------------------|
| rgname | hci-demo | Name of Resource Group |
| rglocation | East US | Location of Resource Group |
| storageaccname | kcnsrarcsa | Name of Storage Account |
| storagecontname1 | sakcnsmonpoc016 | Name of Storage Container for storing python zip package |
| storagecontname2 | sakcnsmonpoc017 | Name of Storage Container for storing input json file |
| zipfl | createaksalertrules.zip | Name of python zip package |
| jsnfl | aksfuncattributes.json | Name of input json file |
| serviceplanname | kcns-arc-mmappsp-vmalert-001 | Name of app service plan |
| appinsightname | appi-arc-kcns-basemm-dev-001 | Name of app insight plan |
| kvname | kcnsarckv | Name of keyvault where secrets are stored |
| kvrgname | hci-demo | Name of Keyvault resource group |
| uaminame | uaminame | Name of User assigned managed identity |
| uamiresourcegroup | hci-demo | Resource group of User assigned managed identity |
| funcappname | kcns-arc-fapp | Name of Function App |
| agid | /subscriptions/xxxxxxxxxxxxxxxxxx/resourceGroups  | ID of metric alert action group |
       |   /xxxxxxxxxxxxxx/providers/microsoft.insights/   |                               
       |    actionGroups/metric-alert-ag                   |                                         
| tags | {} | Tag values |
