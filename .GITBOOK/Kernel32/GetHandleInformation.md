## GetHandleInformation

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetHandleInformation(
   IntPtr hObject,
   out uint lpdwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-gethandleinformation)
