## CreateConsoleScreenBuffer

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern IntPtr CreateConsoleScreenBuffer(
   uint dwDesiredAccess,
   uint dwShareMode,
   IntPtr lpSecurityAttributes,
   uint dwFlags,
   IntPtr lpScreenBufferData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/createconsolescreenbuffer)
