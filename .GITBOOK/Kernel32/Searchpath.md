## Searchpath

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint SearchPath(string lpPath,
   string lpFileName,
   string lpExtension,
   uint nBufferLength,
   [Out] StringBuilder lpBuffer,
   IntPtr lpFilePart
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/processenv/nf-processenv-searchpathw)
