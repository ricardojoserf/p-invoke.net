## UnRegisterTypeLib

```
[DllImport("oleaut32.dll", CharSet = CharSet.Unicode, PreserveSig = false)]
public static extern void UnRegisterTypeLib(
   [MarshalAs(
   UnmanagedType.LPStruct)] Guid libID,
   short wVerMajor,
   short wVerMinor,
   int lcid,
   SYSKIND syskind
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-unregistertypelib)
