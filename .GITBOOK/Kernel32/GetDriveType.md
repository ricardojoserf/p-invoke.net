## GetDriveType

```
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetDriveType(
   string lpRootPathName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdrivetypew)
