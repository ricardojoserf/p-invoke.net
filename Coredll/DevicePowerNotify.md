## DevicePowerNotify

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr DevicePowerNotify(
   IntPtr h,
   DevicePowerRequirement poReq,
   int Level
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ktmw32/nf-ktmw32-devicepowernotify)
