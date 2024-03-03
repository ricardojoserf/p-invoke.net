## UnpackDDElParam

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UnpackDDElParam(
   uint msg,
   IntPtr lParam,
   out IntPtr puiLo,
   out IntPtr puiHi
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dde/nf-dde-unpackddelparam)
