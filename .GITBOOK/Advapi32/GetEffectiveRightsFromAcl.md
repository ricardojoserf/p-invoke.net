## GetEffectiveRightsFromAcl

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetEffectiveRightsFromAcl(
   IntPtr pAcl,
   ref TRUSTEE pTrustee,
   out ACCESS_MASK pAccessRights
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-geteffectiverightsfromacla)
