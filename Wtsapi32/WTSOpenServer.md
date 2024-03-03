## WTSOpenServer

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern IntPtr WTSOpenServer(
   string pServerName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsopenservera)
