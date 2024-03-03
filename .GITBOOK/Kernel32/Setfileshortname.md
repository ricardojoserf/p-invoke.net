## Setfileshortname

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetFileShortName(IntPtr hFile,
   string lpShortName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setfileshortnamea)
