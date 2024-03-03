## DragObject

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DragObject(
   IntPtr hwndParent,
   IntPtr hwndFrom,
   uint fmt,
   IntPtr data,
   IntPtr hcur
);
```

