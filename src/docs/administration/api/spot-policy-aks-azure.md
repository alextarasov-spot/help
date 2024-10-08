# Spot Policy in Azure (AKS)

This is the latest Spot policy in Azure:
```json
{
    "properties": {
        "roleName": "Spot Ocean 2.0 Permissions",
        "description": "",
        "assignableScopes": [
          ],
        "permissions": [
            {
                "actions": [
                    "Microsoft.ContainerService/managedClusters/*",
                    "Microsoft.Compute/diskEncryptionSets/read",
                    "Microsoft.Compute/proximityPlacementGroups/write",
                    "Microsoft.Compute/disks/delete",
                    "Microsoft.Compute/disks/read",
                    "Microsoft.Compute/disks/write",
                    "Microsoft.Compute/locations/DiskOperations/read",
                    "Microsoft.Compute/snapshots/delete",
                    "Microsoft.Compute/snapshots/read",
                    "Microsoft.Compute/snapshots/write",
                    "Microsoft.Compute/locations/vmSizes/read",
                    "Microsoft.Compute/locations/operations/read",
                    "Microsoft.Compute/virtualMachines/*",
                    "Microsoft.Compute/virtualMachineScaleSets/*",
                    "Microsoft.OperationalInsights/workspaces/sharedkeys/read",
                    "Microsoft.OperationalInsights/workspaces/read",
                    "Microsoft.OperationsManagement/solutions/write",
                    "Microsoft.OperationsManagement/solutions/read",
                    "Microsoft.ManagedIdentity/userAssignedIdentities/assign/action",
                    "Microsoft.Storage/storageAccounts/delete",
                    "Microsoft.Storage/storageAccounts/listKeys/action",
                    "Microsoft.Storage/storageAccounts/read",
                    "Microsoft.Storage/storageAccounts/write",
                    "Microsoft.Storage/operations/read",
                    "Microsoft.Network/virtualNetworks/joinLoadBalancer/action",
                    "Microsoft.Network/loadBalancers/delete",
                    "Microsoft.Network/loadBalancers/read",
                    "Microsoft.Network/loadBalancers/write",
                    "Microsoft.Network/publicIPAddresses/delete",
                    "Microsoft.Network/publicIPAddresses/read",
                    "Microsoft.Network/publicIPAddresses/write",
                    "Microsoft.Network/publicIPAddresses/join/action",
                    "Microsoft.Network/networkSecurityGroups/read",
                    "Microsoft.Network/networkSecurityGroups/write",
                    "Microsoft.Network/routeTables/read",
                    "Microsoft.Network/routeTables/routes/delete",
                    "Microsoft.Network/routeTables/routes/read",
                    "Microsoft.Network/routeTables/routes/write",
                    "Microsoft.Network/routeTables/write",
                    "Microsoft.Network/applicationGateways/read",
                    "Microsoft.Network/applicationGateways/write",
                    "Microsoft.Network/virtualNetworks/subnets/join/action",
                    "Microsoft.Network/publicIPAddresses/join/action",
                    "Microsoft.Network/publicIPPrefixes/join/action",
                    "Microsoft.Network/networkInterfaces/read",
                    "Microsoft.Network/networkInterfaces/write",
                    "Microsoft.Network/virtualNetworks/read",
                    "Microsoft.Network/virtualNetworks/subnets/read",
                    "Microsoft.Network/networkSecurityGroups/write",
                    "Microsoft.Network/networkSecurityGroups/read",
                    "Microsoft.Network/virtualNetworks/subnets/join/action",
                    "Microsoft.Network/routeTables/routes/read",
                    "Microsoft.Network/routeTables/routes/write",
                    "Microsoft.Network/privatednszones/*",
                    "Microsoft.Resources/subscriptions/resourceGroups/read"
                ],
                "notActions": [],
                "dataActions": [
                    "Microsoft.Storage/storageAccounts/blobServices/containers/blobs/write"
                ],
                "notDataActions": []
            }
        ]
    }
}

```
