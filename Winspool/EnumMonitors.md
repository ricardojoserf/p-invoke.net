## EnumMonitors

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumMonitors(
   string pName,
   uint Level,
   IntPtr pMonitors,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/enummonitors)
