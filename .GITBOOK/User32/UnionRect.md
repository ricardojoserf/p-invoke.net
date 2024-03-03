## UnionRect

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UnionRect(
   out RECT lprcDst,
   [In] ref RECT lprcSrc1,
   [In] ref RECT lprcSrc2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-unionrect)
