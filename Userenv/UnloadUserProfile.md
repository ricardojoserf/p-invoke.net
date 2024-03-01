## UnloadUserProfile

```
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool UnloadUserProfile(
   IntPtr hToken,
   IntPtr lpProfileInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-unloaduserprofile)
