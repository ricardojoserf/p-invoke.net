## SetBoundsRect

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint SetBoundsRect(
   IntPtr hdc,
   [In] ref RECT lprect,
   uint flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setboundsrect)
