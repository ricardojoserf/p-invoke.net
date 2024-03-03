## CreateProcessAsUser

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateProcessAsUser(
   IntPtr hToken,
   string lpApplicationName,
   string lpCommandLine,
   ref SECURITY_ATTRIBUTES lpProcessAttributes,
   ref SECURITY_ATTRIBUTES lpThreadAttributes,
   [MarshalAs(UnmanagedType.Bool)] bool bInheritHandles,
   uint dwCreationFlags,
   IntPtr lpEnvironment,
   string lpCurrentDirectory,
   ref STARTUPINFO lpStartupInfo,
   out PROCESS_INFORMATION lpProcessInformation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessasusera)
