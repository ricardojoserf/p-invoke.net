## LookupAccountSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LookupAccountSid(
   string lpSystemName,
   IntPtr Sid,
   StringBuilder Name,
   ref uint cbName,
   StringBuilder ReferencedDomainName,
   ref uint cchReferencedDomainName,
   out SID_NAME_USE peUse
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupaccountsida)
