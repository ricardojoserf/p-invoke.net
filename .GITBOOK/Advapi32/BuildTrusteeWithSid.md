## BuildTrusteeWithSid

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern void BuildTrusteeWithSid(
   ref TRUSTEE pTrustee,
   IntPtr pSid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithsida)
