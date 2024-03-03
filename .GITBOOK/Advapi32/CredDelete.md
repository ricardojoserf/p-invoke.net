## CredDelete

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CredDelete(
   string TargetName,
   uint Type,
   uint Flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-creddeletea)
