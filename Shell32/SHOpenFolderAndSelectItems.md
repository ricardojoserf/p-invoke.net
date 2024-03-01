## SHOpenFolderAndSelectItems

```
[DllImport("shell32.dll")]
public static extern int SHOpenFolderAndSelectItems(
   IntPtr pidlFolder,
   uint cidl,
   [MarshalAs(UnmanagedType.LPArray)] IntPtr[] apidl,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shopenfolderandselectitems)
