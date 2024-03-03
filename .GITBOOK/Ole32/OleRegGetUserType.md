## OleRegGetUserType

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleRegGetUserType(
   ref Guid clsid,
   uint dwFormOfType,
   out IntPtr pszUserType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olereggetusertype)
