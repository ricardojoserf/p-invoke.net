## GetClipBox

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetClipBox(
   IntPtr hdc,
   out RECT lprect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getclipbox)
