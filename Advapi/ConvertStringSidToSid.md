## ConvertStringSidToSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertStringSidToSid(
   string StringSid,
   out IntPtr Sid
);
```

Microsoft documentation: (TODO)
