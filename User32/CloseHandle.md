## CloseHandle

```
[DllImport("kernel32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CloseHandle(
   IntPtr hObject
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-closehandle)
