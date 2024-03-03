## CeRunAppAtTime

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeRunAppAtTime(
   string lpszAppName,
   FILETIME* pFileTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/embedded/ms908103(v=msdn.10))
