## CertSrvIsServerOnline

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CertSrvIsServerOnline(
   string wszConfig
);
```


