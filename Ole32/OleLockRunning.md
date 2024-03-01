## OleLockRunning

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleLockRunning(
   IOleObject pObject,
   [MarshalAs(UnmanagedType.Bool)] bool fLock,
   [MarshalAs(UnmanagedType.Bool)] bool fLastUnlockCloses
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olelockrunning)
