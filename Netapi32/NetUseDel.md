## NetUseDel

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUseDel(
   string UncServerName,
   string UseName,
   uint ForceCond
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmuse/nf-lmuse-netusedel)
