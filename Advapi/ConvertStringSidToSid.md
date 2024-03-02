## ConvertStringSidToSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertStringSidToSid(
   string StringSid,
   out IntPtr Sid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertstringsidtosida)
