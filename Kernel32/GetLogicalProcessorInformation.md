## GetLogicalProcessorInformation

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetLogicalProcessorInformation(
   IntPtr Buffer,
   ref uint ReturnLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getlogicalprocessorinformation)
