## MsiViewFetch

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiViewFetch(
   IntPtr hView,
   out IntPtr hRecord
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msiviewfetch)
