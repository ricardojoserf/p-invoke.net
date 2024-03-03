## RegQueryValueEx

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RegQueryValueEx(
   IntPtr hKey,
   string lpValueName,
   IntPtr lpReserved,
   ref int lpType,
   IntPtr lpData,
   ref int lpcbData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvalueexw)
