## QueryPathOfRegTypeLib

```
[DllImport("Comdlg32.dll", SetLastError = true)]
public static extern HRESULT QueryPathOfRegTypeLib(
   [in] ref Guid guid,
   ushort wMaj,
   ushort wMin,
   ushort lcid,
   out IntPtr lpbstrPath
);
```

[Microsoft documentation](TODO)
