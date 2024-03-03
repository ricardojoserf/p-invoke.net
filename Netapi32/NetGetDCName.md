## NetGetDCName

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetGetDCName(
   string ServerName,
   string DomainName,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netgetdcname#:~:text=The%20NetGetDCName%20function%20returns%20the,should%20call%20the%20DsGetDcName%20function.)
