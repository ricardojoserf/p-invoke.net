## FindFirstFile

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFindHandle FindFirstFile(
   string lpFileName,
   out WIN32_FIND_DATA lpFindFileData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findfirstfilew)
