## PlaySound

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool PlaySound(
   string pszSound,
   IntPtr hmod,
   uint fdwSound
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-playsoundw)
