## LPtoDP

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool LPtoDP(
   IntPtr hdc,
   [In,
   Out] ref POINT lpPoints,
   int nCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-lptodp)
