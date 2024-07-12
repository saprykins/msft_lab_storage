myLocation="westeurope"

echo $myLocation

myStorageAcct="sarmytestysstorageaccoun"

resource_groups=$(az group list --query "[].name" --output tsv)  
