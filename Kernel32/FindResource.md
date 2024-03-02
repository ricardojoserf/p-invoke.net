## FindResource

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FindResource(
   IntPtr hModule,
   IntPtr lpName,
   IntPtr lpType
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findresourcea)
