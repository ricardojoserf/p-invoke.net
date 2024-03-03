## Sethandleinformation

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetHandleInformation(IntPtr hObject,
   uint dwMask,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-sethandleinformation)
