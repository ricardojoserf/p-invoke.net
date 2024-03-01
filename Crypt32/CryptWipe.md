## CryptWipe

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern void CryptWipe(
   IntPtr pv,
   uint cb
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptwipe)
