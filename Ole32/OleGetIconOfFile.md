## OleGetIconOfFile

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleGetIconOfFile(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszPath,
   [MarshalAs(UnmanagedType.Bool)] bool fUseFileAsLabel,
   out IntPtr phicon
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olegeticonoffile)
