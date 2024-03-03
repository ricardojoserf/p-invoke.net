## connect

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int connect(
   IntPtr s,
   ref sockaddr_in name,
   int namelen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/credentials/certifications/connect-cert-profile-to-learn)
