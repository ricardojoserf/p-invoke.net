## DevicePowerNotify

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr DevicePowerNotify(
   IntPtr h,
   DevicePowerRequirement poReq,
   int Level
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/ms896927(v=msdn.10))
