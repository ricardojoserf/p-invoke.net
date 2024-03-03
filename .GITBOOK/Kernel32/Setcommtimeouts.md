## Setcommtimeouts

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetCommTimeouts(IntPtr hFile,
   ref COMMTIMEOUTS lpCommTimeouts
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommtimeouts)
