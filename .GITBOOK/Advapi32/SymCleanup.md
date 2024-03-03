## SymCleanup

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SymCleanup(
   IntPtr hProcess
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dbghelp/nf-dbghelp-symcleanup)
