## GetWindowPos

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetWindowPos(
   IntPtr hWnd,
   out POINT lpPoint
);
```

