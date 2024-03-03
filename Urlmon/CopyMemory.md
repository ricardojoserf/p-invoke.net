## CopyMemory

```csharp
[DllImport("urlmon.dll", EntryPoint = "CopyMemory", SetLastError = false)]
public static extern void CopyMemory(
   IntPtr dest,
   IntPtr src,
   uint count
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/legacy/aa366535(v=vs.85))
