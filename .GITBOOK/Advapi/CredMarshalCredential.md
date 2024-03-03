## CredMarshalCredential

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CredMarshalCredential(
   uint Type,
   IntPtr Credential,
   out IntPtr MarshaledCredential
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credmarshalcredentiala)
