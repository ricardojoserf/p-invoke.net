## CredRead

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CredRead(
   string TargetName,
   uint Type,
   uint Flags,
   out IntPtr Credential
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credreada)
