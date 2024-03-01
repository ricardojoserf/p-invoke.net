## AdjustTokenPrivileges

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool AdjustTokenPrivileges(
   IntPtr TokenHandle,
   [MarshalAs(UnmanagedType.Bool)] bool DisableAllPrivileges,
   ref TOKEN_PRIVILEGES NewState,
   uint BufferLength,
   IntPtr PreviousState,
   IntPtr ReturnLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-adjusttokenprivileges)
