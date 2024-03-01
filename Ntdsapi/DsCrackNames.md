## DsCrackNames

```
[DllImport("ntdsapi.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int DsCrackNames(
   IntPtr hDS,
   DS_NAME_FLAGS flags,
   DS_NAME_FORMAT formatOffered,
   DS_NAME_FORMAT formatDesired,
   uint cNames,
   string[] rpNames,
   out IntPtr ppResult
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ntdsapi/nf-ntdsapi-dscracknamesw)
