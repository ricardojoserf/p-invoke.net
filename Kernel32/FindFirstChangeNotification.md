## FindFirstChangeNotification

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFindHandle FindFirstChangeNotification(
   string lpPathName,
   [MarshalAs(UnmanagedType.Bool)] bool bWatchSubtree,
   uint dwNotifyFilter
);
```

Microsoft documentation: (TODO)
