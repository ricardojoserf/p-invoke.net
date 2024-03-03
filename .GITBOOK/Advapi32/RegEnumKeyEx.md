## RegEnumKeyEx

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegEnumKeyEx(
   IntPtr hKey,
   uint dwIndex,
   StringBuilder lpName,
   ref uint lpcName,
   IntPtr lpReserved,
   IntPtr lpClass,
   IntPtr lpcClass,
   IntPtr lpftLastWriteTime
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumkeyexa)
