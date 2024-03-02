## midiOutGetErrorText

```
[DllImport("winmm.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern uint midiOutGetErrorText(
   uint mmrError,
   StringBuilder pszText,
   uint cchText
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midioutgeterrortext)
