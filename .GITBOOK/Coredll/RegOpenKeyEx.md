## RegOpenKeyEx

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RegOpenKeyEx(
   IntPtr hKey,
   string lpSubKey,
   int ulOptions,
   int samDesired,
   out IntPtr phkResult
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeyexw)
