## FindResourceEx

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FindResourceEx(
   IntPtr hModule,
   IntPtr lpType,
   IntPtr lpName,
   ushort wLanguage,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findresourceexa)
