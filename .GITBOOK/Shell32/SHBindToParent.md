## SHBindToParent

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHBindToParent(
   IntPtr hwnd,
   [MarshalAs(UnmanagedType.LPWStr)] string pidl,
   ref IntPtr ppidlLast,
   out IntPtr ppsi,
   ref Guid riid,
   out IntPtr ppv,
   uint dwAttr
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shbindtoparent)
