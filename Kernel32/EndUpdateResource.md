## EndUpdateResource

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EndUpdateResource(
   IntPtr hUpdate,
   [MarshalAs(UnmanagedType.Bool)] bool fDiscard
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-endupdateresourcew)
