## OleCreatePropertyFrame

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreatePropertyFrame(
   IntPtr hwndOwner,
   uint x,
   uint y,
   [MarshalAs(
   UnmanagedType.LPWStr)] string lpszCaption,
   uint cObjects,
   [MarshalAs(
   UnmanagedType.Interface)] ref object ppUnk,
   uint cPages,
   IntPtr pPageClsID,
   uint lcid,
   uint dwReserved,
   IntPtr pvReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/olepro32/nf-olepro32-olecreatepropertyframe)
