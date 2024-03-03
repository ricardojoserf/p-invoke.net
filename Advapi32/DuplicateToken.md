## DuplicateToken

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DuplicateToken(
   IntPtr existingTokenHandle,
   uint securityImpersonationLevel,
   ref IntPtr duplicateTokenHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-duplicatetoken)
