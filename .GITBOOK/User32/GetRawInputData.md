## GetRawInputData

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint GetRawInputData(
   IntPtr hRawInput,
   uint uiCommand,
   IntPtr pData,
   ref uint pcbSize,
   uint cbSizeHeader
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getrawinputdata)
