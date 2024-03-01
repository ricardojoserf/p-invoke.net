## CertEnumSubjectInSortedCTL

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertEnumSubjectInSortedCTL(
   IntPtr pCtlContext,
   ref IntPtr ppvNextSubject,
   ref IntPtr ppvNextEntry
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certenumsubjectinsortedctl)
