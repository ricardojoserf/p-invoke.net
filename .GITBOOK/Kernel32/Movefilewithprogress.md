## Movefilewithprogress

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool MoveFileWithProgress(string lpExistingFileName,
   string lpNewFileName,
   CopyProgressRoutine lpProgressRoutine,
   IntPtr lpData,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-movefilewithprogressw)
