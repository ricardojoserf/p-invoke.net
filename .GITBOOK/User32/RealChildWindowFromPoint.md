## RealChildWindowFromPoint

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr RealChildWindowFromPoint(
   IntPtr hwndParent,
   POINT ptParentClientCoords
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-realchildwindowfrompoint)
