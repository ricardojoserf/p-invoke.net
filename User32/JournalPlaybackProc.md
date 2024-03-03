## JournalPlaybackProc

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr JournalPlaybackProc(
   int code,
   IntPtr wParam,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/winmsg/journalplaybackproc)
