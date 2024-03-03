## FreeLibrary

```
[DllImport("kernel32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FreeLibrary(
   IntPtr hLibModule
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-freelibrary)
