## HttpSetServiceConfiguration

```csharp
[DllImport("Httpapi.dll", SetLastError = true)]
public static extern uint HttpSetServiceConfiguration(
   IntPtr ServiceIntPtr,
   HTTP_SERVICE_CONFIG_ID ConfigId,
   IntPtr pConfigInformation,
   uint ConfigInformationLength,
   IntPtr pOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/http/nf-http-httpsetserviceconfiguration)
