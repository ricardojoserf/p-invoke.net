## StgIsStorageFile

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgIsStorageFile(
   [MarshalAs(UnmanagedType.LPWStr)] string pwcsName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgisstoragefile)
