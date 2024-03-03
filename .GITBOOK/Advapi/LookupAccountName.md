## LookupAccountName

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LookupAccountName(
   string lpSystemName,
   string lpAccountName,
   IntPtr Sid,
   ref uint cbSid,
   StringBuilder ReferencedDomainName,
   ref uint cchReferencedDomainName,
   out SID_NAME_USE peUse
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupaccountnamea)
