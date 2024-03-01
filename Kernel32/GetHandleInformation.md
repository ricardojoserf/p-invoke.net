## GetHandleInformation

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetHandleInformation(
   IntPtr hObject,
   out uint lpdwFlags
);
```

Microsoft documentation: (TODO)
