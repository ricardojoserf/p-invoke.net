## PlaySound

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool PlaySound(
   string pszSound,
   IntPtr hmod,
   uint fdwSound
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/dd743680(v=vs.85))
