## PostKeybdMessage

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool PostKeybdMessage(
   IntPtr hwnd,
   uint vKey,
   uint flags,
   uint cRepeat,
   uint cCode,
   uint status
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/ms865881(v=msdn.10))
