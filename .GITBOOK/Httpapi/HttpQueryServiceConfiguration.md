## HttpQueryServiceConfiguration

```csharp
[DllImport("Httpapi.dll", SetLastError = true)]
public static extern uint HttpQueryServiceConfiguration(
   IntPtr ServiceIntPtr,
   HTTP_SERVICE_CONFIG_ID ConfigId,
   IntPtr pInputConfigInfo,
   uint InputConfigInfoLength,
   IntPtr pOutputConfigInfo,
   uint OutputConfigInfoLength,
   out uint pReturnLength,
   IntPtr pOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/http/nf-http-httpqueryserviceconfiguration)
