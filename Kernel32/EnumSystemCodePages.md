## EnumSystemCodePages

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumSystemCodePages(
   EnumCodePageProc lpCodePageEnumProc,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemcodepagesa)
