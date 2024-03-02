## Securezeromemory

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SecureZeroMemory(IntPtr ptr,
   UIntPtr cnt
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/legacy/aa366877(v=vs.85))
