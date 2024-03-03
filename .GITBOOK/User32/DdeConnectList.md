## DdeConnectList

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeConnectList(
   IntPtr idInst,
   IntPtr hszService,
   IntPtr hszTopic,
   IntPtr hConvList,
   IntPtr pCC
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddeconnectlist)
