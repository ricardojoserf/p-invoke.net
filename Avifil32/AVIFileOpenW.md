## AVIFileOpenW

```
[DllImport("Avifil32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint AVIFileOpenW(
   ref IntPtr ppfile,
   [MarshalAs(UnmanagedType.LPWStr)] string szFile,
   uint uMode,
   IntPtr lpHandler
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/vfw/nf-vfw-avifileopenw)
