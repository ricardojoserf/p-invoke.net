## OleNoteObjectVisible

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleNoteObjectVisible(
   IOleObject pObject,
   [MarshalAs(UnmanagedType.Bool)] bool fVisible
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olenoteobjectvisible)
