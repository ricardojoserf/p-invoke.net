## CopyMetaFile

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CopyMetaFile(
   IntPtr hemf,
   string filename
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-copymetafilea#:~:text=The%20CopyMetaFile%20function%20copies%20the,are%20recommended%20for%20new%20applications.)
