## DestroyPrivateObjectSecurity

```csharp
[DllImport("advapi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DestroyPrivateObjectSecurity(
   IntPtr ObjectDescriptor
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-destroyprivateobjectsecurity)
