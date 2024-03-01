## AttachThreadInput

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AttachThreadInput(
   uint idAttach,
   uint idAttachTo,
   [MarshalAs(UnmanagedType.Bool)] bool fAttach
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-attachthreadinput)
