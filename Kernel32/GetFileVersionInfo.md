## GetFileVersionInfo

```
[DllImport("Version.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetFileVersionInfo(
   string lptstrFilename,
   uint dwHandle,
   uint dwLen,
   IntPtr lpData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winver/nf-winver-getfileversioninfow)
