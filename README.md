Sample appsettings.json
Goes next to `ServiceBusTopicTriggerCSharp` directory

```json
{
  "IsEncrypted": false,
  "Values": {
    "AzureWebJobsStorage": "",
    "AzureWebJobsServiceBus": "Endpoint=sb://trackbus.servicebus.windows.net/;SharedAccessKeyName=RootManageSharedAccessKey;SharedAccessKey=secretsectretsmYYRGc99egLOzO8hEJkL4U=",
    "NotificationHubConnectionString": "Endpoint=sb://tracktech.servicebus.windows.net/;SharedAccessKeyName=DefaultFullSharedAccessSignature;SharedAccessKey=secretsecretCwbOPOdbCiBhw1Q2lSsR6w1g=",
    "hubName": "TTNHub"
  }
}
```