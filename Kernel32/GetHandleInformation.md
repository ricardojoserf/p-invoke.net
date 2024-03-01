## GetHandleInformation

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetHandleInformation(
   IntPtr hObject,
   out uint lpdwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-gethandleinformation)
