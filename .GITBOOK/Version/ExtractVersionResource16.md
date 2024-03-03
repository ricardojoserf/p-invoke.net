## ExtractVersionResource16

```csharp
[DllImport("version.dll", SetLastError = true)]
public static extern IntPtr ExtractVersionResource16(
   string lpszFilename,
   IntPtr lpszLang,
   out VS_FIXEDFILEINFO lpFfi
);
```

