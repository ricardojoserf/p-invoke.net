## SHFormatDrive

```csharp
[DllImport("shell32.dll")]
public static extern int SHFormatDrive(
   IntPtr hwnd,
   uint drive,
   uint fmtID,
   uint options
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shformatdrive)
