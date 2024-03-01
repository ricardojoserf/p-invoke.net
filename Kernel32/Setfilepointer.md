## Setfilepointer

```
[DllImport("Kernel32.dll", SetLastError = true)]
public static extern uint SetFilePointer(IntPtr hFile,
   int lDistanceToMove,
   IntPtr lpDistanceToMoveHigh,
   uint dwMoveMethod
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-setfilepointer)
