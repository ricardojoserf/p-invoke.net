## CoGetCurrentProcess

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetCurrentProcess(
   out IntPtr lpdwProcessId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetcurrentprocess)
