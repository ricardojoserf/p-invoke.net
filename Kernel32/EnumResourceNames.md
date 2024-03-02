## EnumResourceNames

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumResourceNames(
   IntPtr hModule,
   IntPtr lpType,
   EnumResNameProc lpEnumFunc,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-enumresourcenamesa#:~:text=The%20EnumResourceNames%20function%20continues%20to,mui%20file%20associated%20with%20it.)
