## StrFormatByteSize

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern IntPtr StrFormatByteSize(
   ulong qdw,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszBuf,
   uint cchBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-strformatbytesizew)
