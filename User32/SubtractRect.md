## SubtractRect

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SubtractRect(
   out RECT lprcDst,
   [In] ref RECT lprcSrc1,
   [In] ref RECT lprcSrc2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-subtractrect)
