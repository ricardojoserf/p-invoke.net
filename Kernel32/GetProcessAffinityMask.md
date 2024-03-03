## GetProcessAffinityMask

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessAffinityMask(
   IntPtr hProcess,
   out IntPtr lpProcessAffinityMask,
   out IntPtr lpSystemAffinityMask
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprocessaffinitymask)
