## FileTimeToDosDateTime

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FileTimeToDosDateTime(
   ref FILETIME lpFileTime,
   out ushort lpFatDate,
   out ushort lpFatTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-filetimetodosdatetime)
