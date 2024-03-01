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

[Microsoft documentation](TODO)
