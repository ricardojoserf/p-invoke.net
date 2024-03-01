## OpenEvent

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr OpenEvent(
   uint dwDesiredAccess,
   bool bInheritHandle,
   string lpName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-openeventw)
