## OleCreatePropertyFrame

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreatePropertyFrame(
   IntPtr hwndOwner,
   uint x,
   uint y,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszCaption,
   uint cObjects,
   [MarshalAs(UnmanagedType.Interface)] ref object ppUnk,
   uint cPages,
   IntPtr pPageClsID,
   uint lcid,
   uint dwReserved,
   IntPtr pvReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/olectl/nf-olectl-olecreatepropertyframe)
