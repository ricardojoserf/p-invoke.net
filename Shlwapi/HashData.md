## HashData

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int HashData(
   IntPtr pbData,
   uint cbData,
   IntPtr pbHash,
   uint cbHash
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-hashdata)
