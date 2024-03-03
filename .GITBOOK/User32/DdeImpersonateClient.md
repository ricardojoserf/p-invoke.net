## DdeImpersonateClient

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeImpersonateClient(
   IntPtr hConv
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddeimpersonateclient)
