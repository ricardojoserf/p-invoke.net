## OemToChar

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool OemToChar(
   string pSrc,
   StringBuilder pDst
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-oemtocharw)
