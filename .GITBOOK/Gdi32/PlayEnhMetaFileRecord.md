## PlayEnhMetaFileRecord

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PlayEnhMetaFileRecord(
   IntPtr hdc,
   IntPtr pht,
   in ENHMETARECORD phtDesc,
   uint chtDesc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-playenhmetafilerecord)
