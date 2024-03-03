## Lstrcpyn

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr lstrcpyn(StringBuilder lpString1,
   string lpString2,
   int iMaxLength
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lstrcpyna)
