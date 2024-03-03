## GetUserProfileDirectory

```csharp
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool GetUserProfileDirectory(
   IntPtr hToken,
   [Out] StringBuilder lpProfileDir,
   ref uint lpcchSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-getuserprofiledirectoryw)
