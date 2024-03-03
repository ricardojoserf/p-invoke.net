## CreateProcessWithLogonW

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateProcessWithLogonW(
   string lpUsername,
   string lpDomain,
   string lpPassword,
   uint dwLogonFlags,
   string lpApplicationName,
   string lpCommandLine,
   uint dwCreationFlags,
   IntPtr lpEnvironment,
   string lpCurrentDirectory,
   ref STARTUPINFO lpStartupInfo,
   out PROCESS_INFORMATION lpProcessInformation
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createprocesswithlogonw)
