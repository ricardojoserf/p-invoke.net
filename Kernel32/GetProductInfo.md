## GetProductInfo

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProductInfo(
   uint dwOSMajorVersion,
   uint dwOSMinorVersion,
   uint dwSpMajorVersion,
   uint dwSpMinorVersion,
   out uint pdwReturnedProductType
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getproductinfo)
