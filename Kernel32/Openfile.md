## Openfile

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr OpenFile(string lpFileName,
   [Out] OFSTRUCT lpReOpenBuff,
   uint uStyle
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openfile)
