## Wow64disablewow64fsredirection

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Wow64DisableWow64FsRedirection(
   out IntPtr OldValue
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wow64apiset/nf-wow64apiset-wow64disablewow64fsredirection)
