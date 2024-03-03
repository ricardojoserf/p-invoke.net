## Readdirectorychangesw

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadDirectoryChangesW(IntPtr hDirectory,
   IntPtr lpBuffer,
   uint nBufferLength,
   [MarshalAs(UnmanagedType.Bool)] bool bWatchSubtree,
   uint dwNotifyFilter,
   out uint lpBytesReturned,
   IntPtr lpOverlapped,
   IntPtr lpCompletionRoutine
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-readdirectorychangesw)
