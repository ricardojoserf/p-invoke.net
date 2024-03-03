## DeactivateActCtx

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DeactivateActCtx(
   uint dwFlags,
   IntPtr ulCookie
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-deactivateactctx)
