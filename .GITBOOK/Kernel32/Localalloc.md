## Localalloc

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr LocalAlloc(uint uFlags,
   UIntPtr uBytes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-localalloc)
