## AuthentiCode

```
[DllImport("wintrust.dll", SetLastError = true)]
public static extern int AuthentiCode(
   IntPtr hwnd,
   IntPtr pgActionID,
   IntPtr pwszFilePath,
   ref CRYPT_PROVIDER_DATA pProvData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wintrust/nf-wintrust-authenticode)
