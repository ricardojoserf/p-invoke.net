## DdeQueryConvInfo

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint DdeQueryConvInfo(
   IntPtr hConv,
   uint idTransaction,
   ref CONVINFO pConvInfo
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddequeryconvinfo)
