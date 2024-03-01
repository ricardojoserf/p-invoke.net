## BuildExplicitAccessWithName

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern uint BuildExplicitAccessWithName(
   ref EXPLICIT_ACCESS pExplicitAccess,
   string pTrusteeName,
   uint AccessPermissions,
   ACCESS_MODE AccessMode,
   uint Inheritance
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildexplicitaccesswithnamea)
