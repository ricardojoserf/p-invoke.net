## OleCreatePictureIndirect

```csharp
[DllImport("oleaut32.dll", SetLastError = true)]
public static extern int OleCreatePictureIndirect(
   [MarshalAs(UnmanagedType.Struct)] ref PICTDESC ppictdesc,
   ref Guid riid,
   [MarshalAs(UnmanagedType.Bool)] bool fOwn,
   [MarshalAs(UnmanagedType.Interface)] out object ppvObj
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/olectl/nf-olectl-olecreatepictureindirect)
