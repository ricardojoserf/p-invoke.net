## GetSystemDirectory

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetSystemDirectory(
   StringBuilder lpBuffer,
   uint uSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemdirectoryw)
