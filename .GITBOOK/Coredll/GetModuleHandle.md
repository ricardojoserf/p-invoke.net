## GetModuleHandle

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr GetModuleHandle(
   string lpModuleName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulehandlea)
