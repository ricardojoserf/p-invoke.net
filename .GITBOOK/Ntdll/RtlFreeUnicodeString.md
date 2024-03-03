## RtlFreeUnicodeString

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void RtlFreeUnicodeString(
   ref UNICODE_STRING UnicodeString
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-rtlfreeunicodestring)
