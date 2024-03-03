## Setcommmask

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetCommMask(IntPtr hFile,
   uint dwEvtMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommmask)
