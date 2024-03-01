## PostKeybdMessage

```
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

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/windows/embedded/ms938032(v=msdn.10))
