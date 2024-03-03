## ScaleWindowExtEx

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ScaleWindowExtEx(
   IntPtr hdc,
   int xn,
   int xd,
   int yn,
   int yd,
   out SIZE lpsz
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-scalewindowextex)
