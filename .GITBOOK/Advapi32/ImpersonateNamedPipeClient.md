## ImpersonateNamedPipeClient

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool ImpersonateNamedPipeClient(
   IntPtr hNamedPipe
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-impersonatenamedpipeclient)
