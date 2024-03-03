## SetWorldTransform

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetWorldTransform(
   IntPtr hdc,
   [In] ref XFORM lpXform
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setworldtransform)
