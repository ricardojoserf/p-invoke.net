## GetRgnBox

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetRgnBox(
   IntPtr hrgn,
   [Out] RECT lpRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getrgnbox)
