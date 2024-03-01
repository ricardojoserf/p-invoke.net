## CheckTokenMembership

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckTokenMembership(
   IntPtr TokenHandle,
   IntPtr SidToCheck,
   [MarshalAs(
   UnmanagedType.Bool)] out bool IsMember
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-checktokenmembership)
