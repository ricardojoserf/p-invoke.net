## GetGUIThreadInfo

```csharp
[DllImport("user32.dll")]
public static extern bool GetGUIThreadInfo(
   uint idThread,
   ref GUITHREADINFO lpgui
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getguithreadinfo)
