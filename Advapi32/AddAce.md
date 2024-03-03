## AddAce

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool AddAce(
   IntPtr pAcl,
   uint dwAceRevision,
   uint dwStartingAceIndex,
   IntPtr pAceList,
   uint nAceListLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-addace)
