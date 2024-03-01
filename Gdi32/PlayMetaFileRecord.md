## PlayMetaFileRecord

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PlayMetaFileRecord(
   IntPtr hdc,
   IntPtr lpHandleTable,
   IntPtr lpMetaRecord,
   uint nHandles
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-playmetafilerecord)
