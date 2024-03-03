## RtlInitializeSid

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlInitializeSid(
   out SID Sid,
   ref SID_IDENTIFIER_AUTHORITY IdentifierAuthority,
   byte SubAuthorityCount
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/ntifs/nf-ntifs-rtlinitializesid)
