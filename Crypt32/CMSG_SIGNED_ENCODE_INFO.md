## CMSG_SIGNED_ENCODE_INFO

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CMSG_SIGNED_ENCODE_INFO(
   IntPtr pcbEncoded,
   ref CMSG_SIGNED_ENCODE_INFO pInfo,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/ns-wincrypt-cmsg_signed_encode_info)
