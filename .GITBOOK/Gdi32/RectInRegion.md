## RectInRegion

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool RectInRegion(
   IntPtr hrgn,
   ref RECT lprect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-rectinregion)
