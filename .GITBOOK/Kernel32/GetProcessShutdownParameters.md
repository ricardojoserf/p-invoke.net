## GetProcessShutdownParameters

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessShutdownParameters(
   IntPtr lpdwLevel,
   IntPtr lpdwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessshutdownparameters)
