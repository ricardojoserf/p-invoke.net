## ImageList_GetIconSize

```csharp
[DllImport("Comctl32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ImageList_GetIconSize(
   IntPtr himl,
   out int cx,
   out int cy
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/commctrl/nf-commctrl-imagelist_geticonsize)
