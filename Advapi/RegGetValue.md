## RegGetValue

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegGetValue(
   IntPtr hkey,
   string lpSubKey,
   string lpValue,
   uint dwFlags,
   out uint pdwType,
   IntPtr pvData,
   ref uint pcbData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetvaluea)
