## waveOutGetErrorText

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint waveOutGetErrorText(
   uint mmrError,
   StringBuilder pszText,
   uint cchText
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveoutgeterrortext)
