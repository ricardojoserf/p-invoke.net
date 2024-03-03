## DosDateTimeToFileTime

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DosDateTimeToFileTime(
   ushort wFatDate,
   ushort wFatTime,
   out FILETIME lpFileTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-dosdatetimetofiletime)
