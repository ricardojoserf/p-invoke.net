## ImageList_Add

```csharp
[DllImport("Comctl32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ImageList_Add(
   IntPtr himl,
   IntPtr hbmImage,
   IntPtr hbmMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/commctrl/nf-commctrl-imagelist_add)
