## AuditEnumerateCategories

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern uint AuditEnumerateCategories(
   Guid pAuditCategories,
   uint dwFlags,
   out uint pCountReturned,
   out IntPtr ppAuditCategoriesArray
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditenumeratecategories)
