## Netbios

```csharp
[DllImport("Netapi32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern NERR Netbios(
   ref NCB ncb
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/nb30/nf-nb30-netbios)
