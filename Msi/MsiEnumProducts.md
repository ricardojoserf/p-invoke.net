## MsiEnumProducts

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiEnumProducts(
   uint iProductIndex,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpProductBuf
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msienumproductsw)
