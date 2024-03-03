## HttpInitialize

```csharp
[DllImport("Httpapi.dll", SetLastError = true)]
public static extern uint HttpInitialize(
   HTTPAPI_VERSION Version,
   uint Flags,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/http/nf-http-httpinitialize)
