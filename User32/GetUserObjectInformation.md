## GetUserObjectInformation

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetUserObjectInformation(
   IntPtr hObj,
   int nIndex,
   IntPtr pvInfo,
   uint nLength,
   out uint lpnLengthNeeded
);
```

Microsoft documentation: (TODO)
