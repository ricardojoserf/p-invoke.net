## DdeSetQualityOfService

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeSetQualityOfService(
   IntPtr hwndClient,
   ref SECURITY_QUALITY_OF_SERVICE pqosNew,
   ref SECURITY_QUALITY_OF_SERVICE pqosPrev
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dde/nf-dde-ddesetqualityofservice)
