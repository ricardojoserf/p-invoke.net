## DeleteObject

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DeleteObject(
   IntPtr hObject
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-deleteobject#:~:text=The%20DeleteObject%20function%20deletes%20a,handle%20is%20no%20longer%20valid.)
