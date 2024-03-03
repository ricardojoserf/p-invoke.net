## OleTranslateAccelerator

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleTranslateAccelerator(
   IOleInPlaceFrame pFrame,
   ref MSG lpmsg
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oletranslateaccelerator)
