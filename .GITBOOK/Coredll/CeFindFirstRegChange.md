## CeFindFirstRegChange

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr CeFindFirstRegChange(
   CeRegChangeNotifyFilter fdwFilter,
   CeRegChangeNotifyFlags fdwChangeFilter,
   uint fWatchSubtree,
   uint dwNotifyThread,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/embedded/aa517116(v=msdn.10))
