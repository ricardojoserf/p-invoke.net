## ExtCreateRegion

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr ExtCreateRegion(
   IntPtr lpx,
   uint nCount,
   [In] RGNDATA lpData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extcreateregion)
