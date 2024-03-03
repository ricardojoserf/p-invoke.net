## ScrollDC

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ScrollDC(
   IntPtr hDC,
   int dx,
   int dy,
   ref RECT lprcScroll,
   ref RECT lprcClip,
   IntPtr hrgnUpdate,
   ref RECT lprcUpdate
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-scrolldc)
