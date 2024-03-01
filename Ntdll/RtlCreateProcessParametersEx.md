## RtlCreateProcessParametersEx

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlCreateProcessParametersEx(
   out IntPtr pProcessParameters,
   IntPtr ImagePathName,
   IntPtr DllPath,
   IntPtr CurrentDirectory,
   IntPtr CommandLine,
   IntPtr Environment,
   IntPtr NTPathName,
   IntPtr WindowTitle,
   IntPtr DesktopInfo,
   IntPtr ShellInfo,
   IntPtr RuntimeData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-rtlcreateprocessparametersex)
