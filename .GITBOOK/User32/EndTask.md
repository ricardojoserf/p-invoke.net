## EndTask

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EndTask(
   IntPtr hWnd,
   [MarshalAs(UnmanagedType.Bool)] bool fShutDown,
   [MarshalAs(UnmanagedType.Bool)] bool fForce
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-endtask)
