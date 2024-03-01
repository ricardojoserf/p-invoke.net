## RegOverridePredefKey

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegOverridePredefKey(
   IntPtr hKey,
   IntPtr hNewHKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regoverridepredefkey)
