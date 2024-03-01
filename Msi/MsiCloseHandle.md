## MsiCloseHandle

```
DllImport("msi.dll", CharSet = CharSet.Auto)
public static extern int MsiEnumPathesEx(
   [MarshalAs(
   UnmanagedType.LPTStr)] string szProduct,
   int dwReserved,
   int iInstall,
   IntPtr szPath,
   ref int pcchPath
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msiapi/nf-msiapi-msiclosehandle)
