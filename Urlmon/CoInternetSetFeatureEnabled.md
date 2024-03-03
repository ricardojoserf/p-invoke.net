## CoInternetSetFeatureEnabled

```csharp
[DllImport("urlmon.dll", SetLastError = true)]
public static extern int CoInternetSetFeatureEnabled(
   int FeatureEntry,
   [MarshalAs(UnmanagedType.U4)] int dwFlags,
   bool fEnable
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms537168(v=vs.85))
