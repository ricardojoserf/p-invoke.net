## GetDefaultCommConfig

```csharp
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetDefaultCommConfig(
   string lpszName,
   ref COMMCONFIG lpCC,
   ref uint lpdwSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getdefaultcommconfigw)
