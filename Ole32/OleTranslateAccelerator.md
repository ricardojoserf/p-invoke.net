## OleTranslateAccelerator

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleTranslateAccelerator(
   IOleInPlaceFrame pFrame,
   ref MSG lpmsg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleidl/nf-oleidl-oletranslateaccelerator)
