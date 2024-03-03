## GetModuleFileName

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetModuleFileName(
   IntPtr hModule,
   StringBuilder lpFilename,
   uint nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulefilenamew)
