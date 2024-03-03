## RtlMoveMemory

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void RtlMoveMemory(
   IntPtr Destination,
   IntPtr Source,
   uint Length
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/devnotes/rtlmovememory)
