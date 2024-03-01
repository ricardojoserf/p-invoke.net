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

[Microsoft documentation](TODO)
