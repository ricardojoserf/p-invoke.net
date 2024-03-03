## DrawEdge

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DrawEdge(
   IntPtr hdc,
   ref RECT qrc,
   uint edge,
   uint grfFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawedge)
