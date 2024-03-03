## CopyFileEx

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CopyFileEx(
   string lpExistingFileName,
   string lpNewFileName,
   CopyProgressRoutine lpProgressRoutine,
   IntPtr lpData,
   ref int pbCancel,
   CopyFileFlags dwCopyFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-copyfileexa)
