## GlobalAlloc

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr GlobalAlloc(
   uint uFlags,
   UIntPtr dwBytes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalalloc)
