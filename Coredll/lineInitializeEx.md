## lineInitializeEx

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int lineInitializeEx(
   IntPtr phLineApp,
   IntPtr hInstance,
   LINECALLBACK lpfnCallback,
   string lpszAppName,
   out int lpdwNumDevs,
   out LINEINITIALIZEEXPARAMS lpLineInitializeExParams
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/tapi/nf-tapi-lineinitializeexw)
