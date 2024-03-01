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

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/bb416347(v%3Dmsdn.10))
