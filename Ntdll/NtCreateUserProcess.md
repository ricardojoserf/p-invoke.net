## NtCreateUserProcess

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtCreateUserProcess(
   out IntPtr ProcessHandle,
   out IntPtr ThreadHandle,
   uint ProcessDesiredAccess,
   uint ThreadDesiredAccess,
   IntPtr ObjectAttributes,
   IntPtr ProcessParameters,
   bool CreateProcessAsSystem,
   IntPtr TokenHandle,
   IntPtr TokenInformation,
   ref PROCESS_INFORMATION ProcessInformation,
   ref STARTUPINFO StartupInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntcreateuserprocess)
