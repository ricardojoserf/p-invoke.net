## GetUserObjectSecurity

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetUserObjectSecurity(
   IntPtr hObj,
   ref SECURITY_INFORMATION pSIRequested,
   IntPtr pSID,
   uint nLength,
   out uint lpnLengthNeeded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getuserobjectsecurity)
