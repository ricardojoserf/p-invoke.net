## CopyImage

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CopyImage(
   IntPtr h,
   uint type,
   int cx,
   int cy,
   uint flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-copyimage)
