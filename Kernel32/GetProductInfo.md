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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getproductinfo)
