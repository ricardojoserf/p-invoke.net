## GetCurrentApplicationUserModelId

```csharp
[DllImport("Shell32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetCurrentApplicationUserModelId(
   ref uint AppModelIDLength,
   StringBuilder AppModelID
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/appmodel/nf-appmodel-getcurrentapplicationusermodelid)
