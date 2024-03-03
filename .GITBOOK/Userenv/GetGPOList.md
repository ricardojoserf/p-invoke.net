## GetGPOList

```
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool GetGPOList(
   [MarshalAs(UnmanagedType.LPWStr)] string lpName,
   IntPtr lpHandler,
   IntPtr lpArgs,
   uint dwFlags,
   IntPtr pGPOList
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-getgpolistw)
