## GetApplicationUserModelId

```
[DllImport("Shell32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetApplicationUserModelId(
   IntPtr hProcess,
   ref uint AppModelIDLength,
   [Out] StringBuilder sbAppModelID
);
```

Microsoft documentation: (TODO)
