## select

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int select(
   int nfds,
   ref fd_set readfds,
   ref fd_set writefds,
   ref fd_set exceptfds,
   ref timeval timeout
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-transact-sql?view=sql-server-ver16)
