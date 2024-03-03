## DrawFrameControl

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DrawFrameControl(
   IntPtr hdc,
   ref RECT lprc,
   uint uType,
   uint uState
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawframecontrol)
