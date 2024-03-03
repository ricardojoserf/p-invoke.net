## CopyAcceleratorTable

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int CopyAcceleratorTable(
   IntPtr hAccelSrc,
   IntPtr lpAccelDst,
   int cAccelEntries
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-copyacceleratortablea)
