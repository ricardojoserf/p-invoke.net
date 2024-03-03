## GetProfilesDirectory

```csharp
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool GetProfilesDirectory(
   [Out] StringBuilder lpProfileDir,
   ref uint lpcchSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-getprofilesdirectoryw)
