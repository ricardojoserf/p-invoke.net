## GetAppliedGPOList

```
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool GetAppliedGPOList(
   uint dwFlags,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pMachineName,
   IntPtr pSidUser,
   IntPtr pGuidExtension,
   out IntPtr ppGPOList
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-getappliedgpolistw)
