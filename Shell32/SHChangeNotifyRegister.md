## SHChangeNotifyRegister

```
[DllImport("shell32.dll")]
public static extern uint SHChangeNotifyRegister(
   IntPtr hwnd,
   uint fSources,
   uint fEvents,
   uint wMsg,
   int cEntries,
   [MarshalAs(UnmanagedType.LPArray)] SHChangeNotifyEntry[] pFsne
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shchangenotifyregister)
