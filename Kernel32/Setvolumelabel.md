## Setvolumelabel

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetVolumeLabel(string lpRootPathName,
   string lpVolumeName
);
```

Microsoft documentation: (TODO)
