## GetDeviceDriverBaseName

```csharp
[DllImport("psapi.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint GetDeviceDriverBaseName(
   IntPtr ImageBase,
   StringBuilder lpBaseName,
   uint nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getdevicedriverbasenamea)
