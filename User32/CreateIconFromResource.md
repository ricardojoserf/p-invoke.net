## CreateIconFromResource

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CreateIconFromResource(
   byte[] presbits,
   uint dwResSize,
   [MarshalAs(UnmanagedType.Bool)] bool fIcon,
   uint dwVer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createiconfromresource)
