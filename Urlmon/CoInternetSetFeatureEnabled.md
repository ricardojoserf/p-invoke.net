## CoInternetSetFeatureEnabled

```
[DllImport("urlmon.dll", SetLastError = true)]
public static extern int CoInternetSetFeatureEnabled(
   int FeatureEntry,
   [MarshalAs(UnmanagedType.U4)] int dwFlags,
   bool fEnable
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/cc288472(v=vs.85))
