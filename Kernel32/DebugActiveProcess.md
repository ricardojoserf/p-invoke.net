## DebugActiveProcess

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DebugActiveProcess(
   uint dwProcessId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-debugactiveprocess)
