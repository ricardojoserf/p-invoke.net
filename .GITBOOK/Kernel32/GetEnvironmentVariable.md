## GetEnvironmentVariable

```csharp
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetEnvironmentVariable(
   string lpName,
   StringBuilder lpBuffer,
   uint nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processenv/nf-processenv-getenvironmentvariablew)
