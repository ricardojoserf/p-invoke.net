## SaferCreateLevel

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SaferCreateLevel(
   SaferScope dwScopeId,
   SaferLevel dwLevelId,
   uint OpenFlags,
   out IntPtr pLevelHandle,
   IntPtr lpReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safercreatelevel)
