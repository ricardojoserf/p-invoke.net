## PlaySound

```
[DllImport("winmm.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool PlaySound(
   string pszSound,
   IntPtr hmod,
   uint fdwSound
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/dd743680(v=vs.85))
