## GetProcAddress

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.FunctionPtr)]
public static extern IntPtr GetProcAddress(
   IntPtr hModule,
   string lpProcName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getprocaddress)
