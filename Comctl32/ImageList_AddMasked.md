## ImageList_AddMasked

```csharp
[DllImport("Comctl32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ImageList_AddMasked(
   IntPtr himl,
   IntPtr hbmImage,
   uint crMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/commctrl/nf-commctrl-imagelist_addmasked)
