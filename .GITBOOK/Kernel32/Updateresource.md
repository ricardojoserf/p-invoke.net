## Updateresource

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool UpdateResource(IntPtr hUpdate,
   string lpType,
   string lpName,
   ushort wLanguage,
   IntPtr lpData,
   uint cbData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-updateresourcew)
