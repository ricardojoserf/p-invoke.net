## Unlockfile

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool UnlockFile(IntPtr hFile,
   uint dwFileOffsetLow,
   uint dwFileOffsetHigh,
   uint nNumberOfBytesToUnlockLow,
   uint nNumberOfBytesToUnlockHigh
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-unlockfile)
