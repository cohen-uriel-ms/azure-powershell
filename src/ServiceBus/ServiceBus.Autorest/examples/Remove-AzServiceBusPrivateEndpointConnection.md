### Example 1: Remove a private endpoint connection from an ServiceBus namespace
```powershell
Remove-AzServiceBusPrivateEndpointConnection -ResourceGroupName myResourceGroup -NamespaceName myNamespace -Name 00000000000
```

Deletes private endpoint connection `00000000000` from an ServiceBus namespace `myNamespace`.
