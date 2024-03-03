## MapGenericMask

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool MapGenericMask(
   ref uint AccessMask,
   ref GENERIC_MAPPING GenericMapping
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-mapgenericmask)
