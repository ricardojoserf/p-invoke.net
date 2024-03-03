## WinIOCTL

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int WinIOCTL(
   uint Ioctl,
   IntPtr InputBuffer,
   uint InputBufferSize,
   IntPtr OutputBuffer,
   uint OutputBufferSize,
   ref uint BytesReturned,
   IntPtr Overlapped
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winioctl/)
