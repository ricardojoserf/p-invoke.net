## CreateProcess

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CreateProcess(
   string lpApplicationName,
   string lpCommandLine,
   IntPtr lpProcessAttributes,
   IntPtr lpThreadAttributes,
   bool bInheritHandles,
   uint dwCreationFlags,
   IntPtr lpEnvironment,
   string lpCurrentDirectory,
   ref STARTUPINFO lpStartupInfo,
   out PROCESS_INFORMATION lpProcessInformation
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessa)
