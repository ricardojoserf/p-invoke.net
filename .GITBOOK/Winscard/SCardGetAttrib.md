## SCardGetAttrib

```csharp
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardGetAttrib(
   IntPtr hCard,
   uint dwAttrId,
   byte[] pbAttr,
   ref uint pcbAttrLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardgetattrib)
