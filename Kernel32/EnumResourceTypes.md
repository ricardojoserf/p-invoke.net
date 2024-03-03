## EnumResourceTypes

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumResourceTypes(
   IntPtr hModule,
   EnumResTypeProc lpEnumFunc,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-enumresourcetypesw)
