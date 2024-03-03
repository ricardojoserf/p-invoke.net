## ConvertSidToStringSid

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertSidToStringSid(
   IntPtr Sid,
   out IntPtr StringSid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertsidtostringsida)
