providers "azurerm"{
features{}
}

resource "azurerm_resource_group_virtualnetwork" "Example"{
name="vijay"
location="sivaramapuram"
addresspace=[10.0.0.0/16]
resource "azurerm_resource_group_virtualnetwork"."Example"."name"
resource "azurerm_resource_group_virtualnetwork"."Example"."location"
}
