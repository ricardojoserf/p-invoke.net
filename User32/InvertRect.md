## InvertRect

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool InvertRect(
   IntPtr hDC,
   [In] ref RECT lprc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-invertrect)
