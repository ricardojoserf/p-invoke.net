## DsMakePasswordCredentials

```
[DllImport("ntdsapi.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int DsMakePasswordCredentials(
   string UserName,
   string Domain,
   string Password,
   out IntPtr pAuthIdentity
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntdsapi/nf-ntdsapi-dsmakepasswordcredentialsw)
