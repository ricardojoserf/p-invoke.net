## Setfilepointerex

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetFilePointerEx(IntPtr hFile,
   long liDistanceToMove,
   out long lpNewFilePointer,
   uint dwMoveMethod
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-setfilepointerex)
