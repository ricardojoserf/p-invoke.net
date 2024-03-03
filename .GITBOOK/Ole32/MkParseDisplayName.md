## MkParseDisplayName

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int MkParseDisplayName(
   IBindCtx pbc,
   [MarshalAs(UnmanagedType.LPWStr)] string szUserName,
   out uint pchEaten,
   out IMoniker ppmk
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-mkparsedisplayname)
