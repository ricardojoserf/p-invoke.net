## SCardDisconnect

```csharp
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardDisconnect(
   IntPtr hCard,
   uint dwDisposition
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scarddisconnect)
