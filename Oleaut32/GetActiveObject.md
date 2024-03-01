## GetActiveObject

```
[DllImport("oleaut32.dll", SetLastError = true)]
public static extern int GetActiveObject(
   [MarshalAs(UnmanagedType.LPStruct)] Guid rclsid,
   IntPtr pvReserved,
   [MarshalAs(UnmanagedType.Interface)] out object ppunk
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-getactiveobject)
