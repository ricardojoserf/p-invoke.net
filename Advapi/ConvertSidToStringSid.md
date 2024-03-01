## ConvertSidToStringSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertSidToStringSid(
   IntPtr Sid,
   out IntPtr StringSid
);
```

[Microsoft documentation](TODO)
