## SetWindowLong

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int SetWindowLong(
   IntPtr hWnd,
   int nIndex,
   int dwNewLong
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowlongw)
