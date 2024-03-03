## GetModuleHandle

```csharp
[DllImport("kernel32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr GetModuleHandle(
   string lpModuleName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulehandlea)
