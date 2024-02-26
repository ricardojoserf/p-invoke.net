1. ActivateActCtx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-activateactctx) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ActivateActCtx(IntPtr hActCtx, out uint lpCookie);

2. AddAtom - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-addatom) - [DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)] public static extern ushort AddAtom(string lpString);

3. AddConsoleAlias - No direct P/Invoke for this function - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/addconsolealias)

4. AddLocalAlternateComputerName - No direct P/Invoke for this function - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-addlocalalternatecomputername)

5. AllocateUserPhysicalPages - No direct P/Invoke for this function - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-allocateuserphysicalpages)

6. AllocConsole - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/allocconsole) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool AllocConsole();

7. AssignProcessToJobObject - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-assignprocesstojobobject) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool AssignProcessToJobObject(IntPtr hJob, IntPtr hProcess);

8. AttachConsole - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/attachconsole) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool AttachConsole(uint dwProcessId);

9. BackupRead - No direct P/Invoke for this function - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-backupread)

10. BackupWrite - No direct P/Invoke for this function - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-backupwrite)

11. Beep - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-beep) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Beep(uint dwFreq, uint dwDuration);

12. BuildCommDCB - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-buildcommdcb) - No direct P/Invoke for this function.

13. CancelIo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-cancelio) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CancelIo(IntPtr hFile);

14. CancelWaitableTimer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-cancelwaitabletimer) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CancelWaitableTimer(IntPtr hTimer);

15. CheckRemoteDebuggerPresent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-checkremotedebuggerpresent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CheckRemoteDebuggerPresent(IntPtr hProcess, [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent);

16. ClearCommBreak - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-clearcommbreak) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ClearCommBreak(IntPtr hFile);

17. ClearCommError - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-clearcommerror) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ClearCommError(IntPtr hFile, out uint lpErrors, ref COMSTAT lpStat);

18. CloseHandle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-closehandle) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CloseHandle(IntPtr hObject);

19. CommConfigDialog - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-commconfigdialog) - No direct P/Invoke for this function.

20. CompareString - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-comparestring) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern int CompareString(uint Locale, uint dwCmpFlags, string lpString1, int cchCount1, string lpString2, int cchCount2);

21. CompareStringEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-comparestringex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern int CompareStringEx(string lpLocaleName, uint dwCmpFlags, string lpString1, int cchCount1, string lpString2, int cchCount2, IntPtr lpVersionInformation, IntPtr lpReserved, IntPtr lParam);

22. ConnectNamedPipe - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-connectnamedpipe) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ConnectNamedPipe(IntPtr hNamedPipe, IntPtr lpOverlapped);

23. ConsoleFunctions - No información directa. ¿Podrías proporcionar más detalles o verificar si es una función específica?

24. ContinueDebugEvent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-continuedebugevent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ContinueDebugEvent(uint dwProcessId, uint dwThreadId, uint dwContinueStatus);

25. Coord - No es una función. ¿Puedes proporcionar más detalles?

26. CopyFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-copyfile) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CopyFile(string lpExistingFileName, string lpNewFileName, [MarshalAs(UnmanagedType.Bool)] bool bFailIfExists);

27. CopyFileEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-copyfileex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CopyFileEx(string lpExistingFileName, string lpNewFileName, LPOVERLAPPED lpProgressRoutine, IntPtr lpData, ref int pbCancel, CopyFileFlags dwCopyFlags);

28. CreateActCtxW - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createactctxw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern IntPtr CreateActCtxW(ref ACTCTX actctx);

29. CreateConsoleScreenBuffer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/createconsolescreenbuffer) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern IntPtr CreateConsoleScreenBuffer(uint dwDesiredAccess, uint dwShareMode, IntPtr lpSecurityAttributes, uint dwFlags, IntPtr lpScreenBufferData);

30. CreateDirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createdirectory) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateDirectory(string lpPathName, IntPtr lpSecurityAttributes);

31. CreateDirectoryEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createdirectoryex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateDirectoryEx(string lpTemplateDirectory, string lpNewDirectory, IntPtr lpSecurityAttributes);

32. CreateEvent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createeventw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern IntPtr CreateEvent(IntPtr lpEventAttributes, [MarshalAs(UnmanagedType.Bool)] bool bManualReset, [MarshalAs(UnmanagedType.Bool)] bool bInitialState, string lpName);

33. CreateFiber - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createfiber) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr CreateFiber(int dwStackSize, LPFIBER_START_ROUTINE lpStartAddress, IntPtr lpParameter);

34. CreateFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createfile) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFileHandle CreateFile(string lpFileName, uint dwDesiredAccess, uint dwShareMode, IntPtr lpSecurityAttributes, uint dwCreationDisposition, uint dwFlagsAndAttributes, IntPtr hTemplateFile);

35. CreateFileMapping - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-createfilemappingw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFileHandle CreateFileMapping(IntPtr hFile, IntPtr lpFileMappingAttributes, uint flProtect, uint dwMaximumSizeHigh, uint dwMaximumSizeLow, string lpName);

36. CreateHardLink - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createhardlink) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateHardLink(string lpFileName, string lpExistingFileName, IntPtr lpSecurityAttributes);

37. CreateIoCompletionPort - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-createiocompletionport) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFileHandle CreateIoCompletionPort(IntPtr FileHandle, IntPtr ExistingCompletionPort, UIntPtr CompletionKey, uint NumberOfConcurrentThreads);

38. CreateJobObject - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi2/nf-jobapi2-createjobobjectw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeJobHandle CreateJobObject(IntPtr lpJobAttributes, string lpName);

39. CreateMailslot - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createmailslotw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeMailslotHandle CreateMailslot(string lpName, uint nMaxMessageSize, uint lReadTimeout, IntPtr lpSecurityAttributes);

40. CreateMemoryResourceNotification - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-creatememoryresourcenotification) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeMemoryResourceNotificationHandle CreateMemoryResourceNotification(MEMORY_RESOURCE_NOTIFICATION_TYPE notificationType);

41. CreateMutex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createmutexw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeWaitHandle CreateMutex(IntPtr lpMutexAttributes, [MarshalAs(UnmanagedType.Bool)] bool bInitialOwner, string lpName);

42. CreateNamedPipe - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-createnamedpipew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafePipeHandle CreateNamedPipe(string lpName, uint dwOpenMode, uint dwPipeMode, uint nMaxInstances, uint nOutBufferSize, uint nInBufferSize, uint nDefaultTimeOut, IntPtr lpSecurityAttributes);

43. CreatePipe - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-createpipe) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreatePipe(out SafeFileHandle hReadPipe, out SafeFileHandle hWritePipe, IntPtr lpPipeAttributes, uint nSize);

44. CreateProcess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateProcess(string lpApplicationName, string lpCommandLine, IntPtr lpProcessAttributes, IntPtr lpThreadAttributes, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandles, uint dwCreationFlags, IntPtr lpEnvironment, string lpCurrentDirectory, ref STARTUPINFO lpStartupInfo, out PROCESS_INFORMATION lpProcessInformation);

45. CreateProcessW - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateProcessW(string lpApplicationName, string lpCommandLine, IntPtr lpProcessAttributes, IntPtr lpThreadAttributes, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandles, uint dwCreationFlags, IntPtr lpEnvironment, string lpCurrentDirectory, ref STARTUPINFO lpStartupInfo, out PROCESS_INFORMATION lpProcessInformation);

46. CreateRemoteThread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createremotethread) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr CreateRemoteThread(IntPtr hProcess, IntPtr lpThreadAttributes, uint dwStackSize, IntPtr lpStartAddress, IntPtr lpParameter, uint dwCreationFlags, IntPtr lpThreadId);

47. CreateSymbolicLink - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createsymboliclinkw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateSymbolicLink(string lpSymlinkFileName, string lpTargetFileName, uint dwFlags);

48. CreateThread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createthread) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr CreateThread(IntPtr lpThreadAttributes, uint dwStackSize, IntPtr lpStartAddress, IntPtr lpParameter, uint dwCreationFlags, IntPtr lpThreadId);

49. CreateTimerQueue - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/threadpoolapiset/nf-threadpoolapiset-createtimerqueue) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeTimerQueueHandle CreateTimerQueue();

50. CreateTimerQueueTimer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/threadpoolapiset/nf-threadpoolapiset-createtimerqueuetimer) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool CreateTimerQueueTimer(out IntPtr phNewTimer, SafeTimerQueueHandle TimerQueue, WAITORTIMERCALLBACK Callback, IntPtr Parameter, uint DueTime, uint Period, uint Flags);

51. CreateToolhelp32Snapshot flags - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-createtoolhelp32snapshot) - [Flags] public enum SnapshotFlags : uint { ... }

52. CreateToolhelp32Snapshot - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-createtoolhelp32snapshot) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeSnapshotHandle CreateToolhelp32Snapshot(SnapshotFlags dwFlags, uint th32ProcessID);

53. CreateWaitableTimer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createwaitabletimerw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeWaitHandle CreateWaitableTimer(IntPtr lpTimerAttributes, [MarshalAs(UnmanagedType.Bool)] bool bManualReset, string lpTimerName);

54. Csepeli László - No es una función conocida de Windows. ¿Puedes proporcionar más detalles?

55. Ctl_Code - No es una función conocida de Windows. ¿Puedes proporcionar más detalles?

56. DeactivateActCtx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-deactivateactctx) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DeactivateActCtx(uint dwFlags, IntPtr ulCookie);

57. DebugActiveProcess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-debugactiveprocess) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DebugActiveProcess(uint dwProcessId);

58. DebugActiveProcessStop - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-debugactiveprocessstop) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DebugActiveProcessStop(uint dwProcessId);

59. DebugBreak - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-debugbreak) - No P/Invoke required.

60. DebugSetProcessKillOnExit - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-debugsetprocesskillonexit) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DebugSetProcessKillOnExit([MarshalAs(UnmanagedType.Bool)] bool KillOnExit);

61. DecryptFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-decryptfilew) - [DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DecryptFile(string lpFileName, uint dwReserved);

62. DefineDosDevice - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-definedosdevicew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DefineDosDevice(uint dwFlags, string lpDeviceName, string lpTargetPath);

63. DeleteAtom - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-deleteatom) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DeleteAtom(ushort nAtom);

64. DeleteCriticalSection - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-deletecriticalsection) - No P/Invoke required.

65. DeleteFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-deletefilew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DeleteFile(string lpFileName);

66. DeleteProcThreadAttributeList - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-deleteprocthreadattributelist) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DeleteProcThreadAttributeList(IntPtr lpAttributeList);

67. DeleteVolumeMountPoint - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-deletevolumemountpointw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DeleteVolumeMountPoint(string lpszVolumeMountPoint);

68. DeviceIoControl - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-deviceiocontrol) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DeviceIoControl(SafeFileHandle hDevice, uint dwIoControlCode, IntPtr lpInBuffer, uint nInBufferSize, IntPtr lpOutBuffer, uint nOutBufferSize, out uint lpBytesReturned, IntPtr lpOverlapped);

69. DnsHostnameToComputerName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-dnshostnametocomputername) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DnsHostnameToComputerName(string Hostname, StringBuilder ComputerName, ref uint nSize);

70. DosDateTimeToFileTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/minwinbase/nf-minwinbase-dosdatetimetofiletime) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DosDateTimeToFileTime(ushort wFatDate, ushort wFatTime, out FILETIME lpFileTime);

71. DuplicateHandle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-duplicatehandle) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool DuplicateHandle(IntPtr hSourceProcessHandle, IntPtr hSourceHandle, IntPtr hTargetProcessHandle, out IntPtr lpTargetHandle, uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, uint dwOptions);

72. EndUpdateResource - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-endupdateresourcew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EndUpdateResource(IntPtr hUpdate, [MarshalAs(UnmanagedType.Bool)] bool fDiscard);

73. EnterCriticalSection - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-entercriticalsection) - No P/Invoke required.

74. EnumDateFormats - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumdateformatsw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumDateFormats(EnumDateFormatsProc lpDateFmtEnumProc, uint Locale, uint dwFlags);

75. EnumerateLocalComputerNames - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-enumeratelocalcomputernamesw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumerateLocalComputerNames(COMPUTER_NAME_FORMAT NameType, uint dwFlags, ref uint nSize);

76. EnumResourceLanguages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-enumresourcelanguagesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumResourceLanguages(IntPtr hModule, IntPtr lpType, IntPtr lpName, EnumResLangProc lpEnumFunc, IntPtr lParam);

77. EnumResourceNames - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-enumresourcenamesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumResourceNames(IntPtr hModule, IntPtr lpType, EnumResNameProc lpEnumFunc, IntPtr lParam);

78. EnumResourceTypes - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-enumresourcetypesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumResourceTypes(IntPtr hModule, EnumResTypeProc lpEnumFunc, IntPtr lParam);

79. EnumSystemCodePages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemcodepages) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumSystemCodePages(EnumCodePageProc lpCodePageEnumProc, uint dwFlags);

80. EnumSystemLocales - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemlocalesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumSystemLocales(EnumLocalesProc lpLocaleEnumProc, uint dwFlags);

81. EnumSystemLocalesEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemlocalesex) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumSystemLocalesEx(EnumLocalesProcEx lpLocaleEnumProc, uint dwFlags, IntPtr lParam);

82. EnumUiLanguages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumuilanguagesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EnumUILanguages(EnumUILanguagesProc lpUILanguageEnumProc, uint dwFlags, IntPtr lParam);

83. EscapeCommFunction - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-escapecommfunction) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool EscapeCommFunction(SafeFileHandle hFile, uint dwFunc);

84. ExitProcess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-exitprocess) - No P/Invoke required.

85. ExpandEnvironmentStrings - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-expandenvironmentstringsw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern uint ExpandEnvironmentStrings(string lpSrc, [Out] StringBuilder lpDst, uint nSize);

86. ExpandEnvironmentStringsA - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-expandenvironmentstringsa) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern uint ExpandEnvironmentStringsA(string lpSrc, [Out] StringBuilder lpDst, uint nSize);

87. FatalExit - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-fatalexit) - No P/Invoke required.

88. Filestream - No es una función conocida de Windows. ¿Puedes proporcionar más detalles?

89. FileTimeToDosDateTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/minwinbase/nf-minwinbase-filetimetodosdatetime) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FileTimeToDosDateTime(ref FILETIME lpFileTime, out ushort lpFatDate, out ushort lpFatTime);

90. FileTimeToLocalFileTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/minwinbase/nf-minwinbase-filetimetolocalfiletime) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FileTimeToLocalFileTime(ref FILETIME lpFileTime, out FILETIME lpLocalFileTime);

91. FileTimeToSystemTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/minwinbase/nf-minwinbase-filetimetosystemtime) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FileTimeToSystemTime(ref FILETIME lpFileTime, out SYSTEMTIME lpSystemTime);

92. FillConsoleOutputCharacter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/consoleapi/nf-consoleapi-fillconsoleoutputcharacterw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FillConsoleOutputCharacter(IntPtr hConsoleOutput, char cCharacter, uint nLength, COORD dwWriteCoord, out uint lpNumberOfCharsWritten);

93. FindAtom - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findatomw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindAtom(string lpString);

94. FindClose - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findclose) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindClose(IntPtr hFindFile);

95. FindCloseChangeNotification - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findclosechangenotification) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindCloseChangeNotification(IntPtr hChangeHandle);

96. FindFirstChangeNotification - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findfirstchangenotificationw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFindHandle FindFirstChangeNotification(string lpPathName, [MarshalAs(UnmanagedType.Bool)] bool bWatchSubtree, uint dwNotifyFilter);

97. FindFirstFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findfirstfilew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFindHandle FindFirstFile(string lpFileName, out WIN32_FIND_DATA lpFindFileData);

98. FindFirstFileEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findfirstfileexw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFindHandle FindFirstFileEx(string lpFileName, FINDEX_INFO_LEVELS fInfoLevelId, out WIN32_FIND_DATA lpFindFileData, FINDEX_SEARCH_OPS fSearchOp, IntPtr lpSearchFilter, uint dwAdditionalFlags);

99. FindFirstVolume - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findfirstvolumew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)] public static extern SafeFindVolumeHandle FindFirstVolume(StringBuilder lpszVolumeName, uint cchBufferLength);

100. FindNextChangeNotification - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findnextchangenotification) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindNextChangeNotification(IntPtr hChangeHandle);

101. FindNextFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findnextfilew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindNextFile(SafeFindHandle hFindFile, out WIN32_FIND_DATA lpFindFileData);

102. FindNextVolume - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findnextvolumew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindNextVolume(SafeFindVolumeHandle hFindVolume, StringBuilder lpszVolumeName, uint cchBufferLength);

103. FindResource - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findresourcew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindResource(IntPtr hModule, IntPtr lpName, IntPtr lpType);

104. FindResourceEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-findresourceexw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FindResourceEx(IntPtr hModule, IntPtr lpType, IntPtr lpName, ushort wLanguage, IntPtr lParam);

105. Findwindow - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-findwindoww) - [DllImport("User32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern IntPtr FindWindow(string lpClassName, string lpWindowName);

106. FlsAlloc - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fibersapi/nf-fibersapi-flsalloc) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint FlsAlloc(FlsCallback lpCallback);

107. FlushConsoleInputBuffer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/consoleapi/nf-consoleapi-flushconsoleinputbuffer) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FlushConsoleInputBuffer(IntPtr hConsoleInput);

108. FlushFileBuffers - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-flushfilebuffers) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FlushFileBuffers(SafeFileHandle hFile);

109. FlushInstructionCache - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-flushinstructioncache) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FlushInstructionCache(IntPtr hProcess, IntPtr lpBaseAddress, uint dwSize);

110. FlushViewOfFile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-flushviewoffile) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FlushViewOfFile(IntPtr lpBaseAddress, uint dwNumberOfBytesToFlush);

111. FoldStringW - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-foldstringw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint FoldStringW(uint dwMapFlags, string lpSrcStr, int cchSrc, StringBuilder lpDestStr, int cchDest);

112. Formatmessage - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-formatmessagew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint FormatMessage(uint dwFlags, IntPtr lpSource, uint dwMessageId, uint dwLanguageId, StringBuilder lpBuffer, uint nSize, IntPtr Arguments);

113. FormatMessageA - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-formatmessagea) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint FormatMessageA(uint dwFlags, IntPtr lpSource, uint dwMessageId, uint dwLanguageId, StringBuilder lpBuffer, uint nSize, IntPtr Arguments);

114. FreeConsole - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-freeconsole) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FreeConsole();

115. FreeLibrary - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-freelibrary) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FreeLibrary(IntPtr hModule);

116. FreeUserPhysicalPages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-freeuserphysicalpages) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool FreeUserPhysicalPages(IntPtr hProcess, ref ulong lpNumberOfPages, ulong[] userPfnArray);

117. GenerateConsoleCtrlEvent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-generateconsolectrlevent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GenerateConsoleCtrlEvent(uint dwCtrlEvent, uint dwProcessGroupId);

118. GetApplicationUserModelId - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shappmgr/nf-shappmgr-getapplicationusermodelid) - [DllImport("Shell32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetApplicationUserModelId(IntPtr hProcess, ref uint AppModelIDLength, [Out] StringBuilder sbAppModelID);

119. GetAtomName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getatomnamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetAtomName(ushort nAtom, StringBuilder lpBuffer, int nSize);

120. GetBinaryType - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getbinarytypew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetBinaryType(string lpApplicationName, out uint lpBinaryType);

121. GetCurrentActCtx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getcurrentactctx) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetCurrentActCtx(out IntPtr phActCtx);

122. GetCurrentApplicationUserModelId - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shappmgr/nf-shappmgr-getcurrentapplicationusermodelid) - [DllImport("Shell32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetCurrentApplicationUserModelId(ref uint AppModelIDLength, [Out] StringBuilder sbAppModelID);

123. GetCurrentConsoleFont - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getcurrentconsolefont) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetCurrentConsoleFont(IntPtr hConsoleOutput, [MarshalAs(UnmanagedType.Bool)] bool bMaximumWindow, out CONSOLE_FONT_INFO lpConsoleCurrentFont);

124. GetCurrentConsoleFontEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getcurrentconsolefontex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetCurrentConsoleFontEx(IntPtr hConsoleOutput, [MarshalAs(UnmanagedType.Bool)] bool bMaximumWindow, out CONSOLE_FONT_INFO_EX lpConsoleCurrentFontEx);

125. GetCurrentDirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getcurrentdirectory) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetCurrentDirectory(uint nBufferLength, StringBuilder lpBuffer);

126. GetCurrentProcess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentprocess) - No P/Invoke required.

127. GetCurrentProcessId - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentprocessid) - No P/Invoke required.

128. GetCurrentProcessorNumber - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getcurrentprocessornumber) - No P/Invoke required.

129. GetCurrentThread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentthread) - No P/Invoke required.

130. GetCurrentThreadId - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentthreadid) - No P/Invoke required.

131. GetDateFormat - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getdateformatw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetDateFormat(uint Locale, uint dwFlags, ref SYSTEMTIME lpDate, string lpFormat, StringBuilder lpDateStr, int cchDate);

132. GetDefaultCommConfig - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getdefaultcommconfigw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetDefaultCommConfig(string lpszName, ref COMMCONFIG lpCC, ref uint lpdwSize);

133. GetDevicePowerState - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getdevicepowerstate) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetDevicePowerState(IntPtr hDevice, [MarshalAs(UnmanagedType.Bool)] out bool pfOn);

134. GetDiskFreeSpace - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdiskfreespacew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetDiskFreeSpace(string lpRootPathName, out uint lpSectorsPerCluster, out uint lpBytesPerSector, out uint lpNumberOfFreeClusters, out uint lpTotalNumberOfClusters);

135. GetDiskFreeSpaceEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdiskfreespaceexw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetDiskFreeSpaceEx(string lpDirectoryName, out ulong lpFreeBytesAvailable, out ulong lpTotalNumberOfBytes, out ulong lpTotalNumberOfFreeBytes);

136. GetDriveType - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdrivetypew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetDriveType(string lpRootPathName);

137. GetEnvironmentVariable - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processenv/nf-processenv-getenvironmentvariablew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetEnvironmentVariable(string lpName, StringBuilder lpBuffer, uint nSize);

138. GetExitCodeProcess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getexitcodeprocess) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetExitCodeProcess(IntPtr hProcess, out uint lpExitCode);

139. GetExitCodeThread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getexitcodethread) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetExitCodeThread(IntPtr hThread, out uint lpExitCode);

140. GetFileAttributes - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileattributesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetFileAttributes(string lpFileName);

141. GetFileAttributesEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileattributesexw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetFileAttributesEx(string lpFileName, GET_FILEEX_INFO_LEVELS fInfoLevelId, ref WIN32_FILE_ATTRIBUTE_DATA lpFileInformation);

142. GetFileInformationByHandle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileinformationbyhandle) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetFileInformationByHandle(SafeFileHandle hFile, out BY_HANDLE_FILE_INFORMATION lpFileInformation);

143. GetFileInformationByHandleEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileinformationbyhandleex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetFileInformationByHandleEx(SafeFileHandle hFile, FILE_INFO_BY_HANDLE_CLASS FileInformationClass, out FILE_STANDARD_INFO lpFileInformation, uint dwBufferSize);

144. GetFileSize - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfilesize) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetFileSize(SafeFileHandle hFile, out uint lpFileSizeHigh);

145. GetFileSizeEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfilesizeex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetFileSizeEx(SafeFileHandle hFile, out ulong lpFileSize);

146. GetFileTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfiletime) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetFileTime(SafeFileHandle hFile, ref FILETIME lpCreationTime, ref FILETIME lpLastAccessTime, ref FILETIME lpLastWriteTime);

147. GetFileType - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfiletype) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetFileType(IntPtr hFile);

148. GetFileVersionInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winver/nf-winver-getfileversioninfow) - [DllImport("Version.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetFileVersionInfo(string lptstrFilename, uint dwHandle, uint dwLen, IntPtr lpData);

149. GetFullPathName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfullpathnamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetFullPathName(string lpFileName, uint nBufferLength, StringBuilder lpBuffer, IntPtr lpFilePart);

150. GetHandleInformation - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-gethandleinformation) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetHandleInformation(IntPtr hObject, out uint lpdwFlags);

151. GetKeyboardType - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getkeyboardtype) - [DllImport("User32.dll")][return: MarshalAs(UnmanagedType.U2)] public static extern ushort GetKeyboardType(uint nTypeFlag);

152. GetLargePageMinimum - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-getlargepageminimum) - No P/Invoke required.

153. GetLastError - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-getlasterror) - No P/Invoke required.

154. GetLocaleInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getlocaleinfow) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetLocaleInfo(uint Locale, uint LCType, StringBuilder lpLCData, uint cchData);

155. GetLocaleInfoEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getlocaleinfoex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern int GetLocaleInfoEx(string lpLocaleName, uint LCType, StringBuilder lpLCData, uint cchData);

156. GetLocalTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getlocaltime) - No P/Invoke required.

157. GetLogicalDrives - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getlogicaldrives) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetLogicalDrives();

158. GetLogicalDriveStrings - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getlogicaldrivestringsw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetLogicalDriveStrings(uint nBufferLength, StringBuilder lpBuffer);

159. GetLogicalProzessorInformation - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getlogicalprocessorinformation) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetLogicalProcessorInformation(IntPtr Buffer, ref uint ReturnLength);

160. GetLongPathName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getlongpathnamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetLongPathName(string lpszShortPath, StringBuilder lpszLongPath, uint cchBuffer);

161. GetMailslotInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getmailslotinfow) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetMailslotInfo(SafeFileHandle hMailslot, IntPtr lpMaxMessageSize, out uint lpNextSize, out uint lpMessageCount, IntPtr lpReadTimeout);

162. GetModuleFileName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulefilenamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetModuleFileName(IntPtr hModule, StringBuilder lpFilename, uint nSize);

163. GetModuleHandle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulehandlew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetModuleHandle(string lpModuleName);

164. GetNamedPipeClientProcessId - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-getnamedpipeclientprocessid) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetNamedPipeClientProcessId(SafePipeHandle hNamedPipe, out uint clientProcessId);

165. GetNativeSystemInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getnativesysteminfo) - No P/Invoke required.

166. GetNumaHighestNodeNumber - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getnumahighestnodenumber) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetNumaHighestNodeNumber(out uint highestNodeNumber);

167. GetNumberOfConsoleMouseButtons - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getnumberofconsolemousebuttons) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetNumberOfConsoleMouseButtons(ref uint lpNumberOfMouseButtons);

168. GetOverlappedResult - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getoverlappedresult) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetOverlappedResult(SafeFileHandle hFile, ref OVERLAPPED lpOverlapped, out uint lpNumberOfBytesTransferred, [MarshalAs(UnmanagedType.Bool)] bool bWait);

169. GetPhysicallyInstalledSystemMemory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getphysicallyinstalledsystemmemory) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetPhysicallyInstalledSystemMemory(out ulong TotalMemoryInKilobytes);

170. GetPriorityClass - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getpriorityclass) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetPriorityClass(IntPtr hProcess);

171. GetPrivateProfileInt - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofileintw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetPrivateProfileInt(string lpAppName, string lpKeyName, int nDefault, string lpFileName);

172. GetPrivateProfileSection - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofilesectionw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetPrivateProfileSection(string lpAppName, IntPtr lpReturnedString, uint nSize, string lpFileName);

173. GetPrivateProfileSectionNames - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofilesectionnamesw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetPrivateProfileSectionNames(IntPtr lpszReturnBuffer, uint nSize, string lpFileName);

174. GetPrivateProfileString - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getprivateprofilestringw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetPrivateProfileString(string lpAppName, string lpKeyName, string lpDefault, StringBuilder lpReturnedString, uint nSize, string lpFileName);

175. GetProcAddress - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getprocaddress) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.FunctionPtr)] public static extern IntPtr GetProcAddress(IntPtr hModule, string lpProcName);

176. GetProcessAffinityMask - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessaffinitymask) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessAffinityMask(IntPtr hProcess, out IntPtr lpProcessAffinityMask, out IntPtr lpSystemAffinityMask);

177. GetProcessDeppolicy - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessdeppolicy) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessDEPPolicy(IntPtr hProcess, out uint lpFlags, [MarshalAs(UnmanagedType.Bool)] out bool lpPermanent);

178. GetProcessHandleCount - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocesshandlecount) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessHandleCount(IntPtr hProcess, out uint pdwHandleCount);

179. GetProcessHeap - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-getprocessheap) - No P/Invoke required.

180. GetProcessHeaps - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-getprocessheaps) - No P/Invoke required.

181. GetProcessId - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessid) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetProcessId(IntPtr Process);

182. GetProcessIdOfThread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessidofthread) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessIdOfThread(IntPtr Thread, out uint ProcessId);

183. GetProcessIoCounters - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessiocounters) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessIoCounters(IntPtr hProcess, out IO_COUNTERS lpIoCounters);

184. GetProcessShutdownParameters - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessshutdownparameters) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessShutdownParameters(IntPtr lpdwLevel, IntPtr lpdwFlags);

185. GetProcessTimes - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocesstimes) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProcessTimes(IntPtr hProcess, out FILETIME lpCreationTime, out FILETIME lpExitTime, out FILETIME lpKernelTime, out FILETIME lpUserTime);

186. GetProductInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getproductinfo) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetProductInfo(uint dwOSMajorVersion, uint dwOSMinorVersion, uint dwSpMajorVersion, uint dwSpMinorVersion, out uint pdwReturnedProductType);

187. GetQueuedCompletionStatus - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-getqueuedcompletionstatus) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetQueuedCompletionStatus(SafeHandle CompletionPort, out uint lpNumberOfBytesTransferred, out IntPtr lpCompletionKey, out IntPtr lpOverlapped, uint dwMilliseconds);

188. GetShortPathName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getshortpathnamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetShortPathName(string lpszLongPath, StringBuilder lpszShortPath, uint cchBuffer);

189. GetStartupInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getstartupinfow) - No P/Invoke required.

190. GetStdHandle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getstdhandle) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetStdHandle(uint nStdHandle);

191. GetStringType - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getstringtypew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetStringType(uint Locale, uint dwInfoType, string lpSrcStr, int cchSrc, out ushort lpCharType);

192. GetStringTypeEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getstringtypeexw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetStringTypeEx(uint Locale, uint dwInfoType, string lpSrcStr, int cchSrc, out ushort lpCharType);

193. GetSystemDefaultLangID - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getsystemdefaultlangid) - No P/Invoke required.

194. GetSystemDefaultLcid - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getsystemdefaultlcid) - No P/Invoke required.

195. GetSystemDefaultUILanguage - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getsystemdefaultuilanguage) - No P/Invoke required.

196. GetSystemDirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemdirectoryw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetSystemDirectory(StringBuilder lpBuffer, uint uSize);

197. GetSystemFileCacheSize - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemfilecachesize) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetSystemFileCacheSize(out uint lpMinimumFileCacheSize, out uint lpMaximumFileCacheSize, out uint lpFlags);

198. GetSystemInfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsysteminfo) - No P/Invoke required.

199. GetSystemPowerStatus - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getsystempowerstatus) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetSystemPowerStatus(out SYSTEM_POWER_STATUS lpSystemPowerStatus);

200. GetSystemPreferredUILanguages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getsystempreferreduilanguages) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetSystemPreferredUILanguages(uint dwFlags, ref uint pulNumLanguages, StringBuilder pwszLanguagesBuffer, ref uint pcchLanguagesBuffer);

201. GetSystemTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemtime) - No P/Invoke required.

202. GetSystemTimeAsFileTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemtimeasfiletime) - No P/Invoke required.

203. GetSystemTimePreciseAsFileTime - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemtimepreciseasfiletime) - No P/Invoke required.

204. GetSystemTimes - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemtimes) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetSystemTimes(out FILETIME lpIdleTime, out FILETIME lpKernelTime, out FILETIME lpUserTime);

205. GetSystemWindowsDirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemwindowsdirectoryw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetSystemWindowsDirectory(StringBuilder lpBuffer, uint uSize);

206. GetSystemWow64Directory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemwow64directoryw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetSystemWow64Directory(StringBuilder lpBuffer, uint uSize);

207. GetTapePosition - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-gettapeposition) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetTapePosition(IntPtr hDevice, uint dwPositionType, out uint lpdwPartition, out uint lpdwOffsetLow, out uint lpdwOffsetHigh);

208. GetTempFileName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-gettempfilenamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetTempFileName(string lpPathName, string lpPrefixString, uint uUnique, StringBuilder lpTempFileName);

209. GetTempPath - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-gettemppathw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetTempPath(uint nBufferLength, StringBuilder lpBuffer);

210. GetThreadContext - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getthreadcontext) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetThreadContext(IntPtr hThread, ref CONTEXT lpContext);

211. GetThreadLocale - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getthreadlocale) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetThreadLocale();

212. GetThreadPriority - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getthreadpriority) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern int GetThreadPriority(IntPtr hThread);

213. GetThreadSelectorEntry - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-getthreadselectorentry) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetThreadSelectorEntry(IntPtr hThread, uint dwSelector, out LDT_ENTRY lpSelectorEntry);

214. GetThreadTimes - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getthreadtimes) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetThreadTimes(IntPtr hThread, out FILETIME lpCreationTime, out FILETIME lpExitTime, out FILETIME lpKernelTime, out FILETIME lpUserTime);

215. GetTickCount - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-gettickcount) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetTickCount();

216. GetTimeFormat - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-gettimeformatw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetTimeFormat(uint Locale, uint dwFlags, ref SYSTEMTIME lpTime, string lpFormat, StringBuilder lpTimeStr, int cchTime);

217. GetTimeZoneInformation - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-gettimezoneinformation) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetTimeZoneInformation(out TIME_ZONE_INFORMATION lpTimeZoneInformation);

218. GetUserDefaultLcid - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getuserdefaultlcid) - No P/Invoke required.

219. GetUserPreferredUILanguages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getuserpreferreduilanguages) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetUserPreferredUILanguages(uint dwFlags, ref uint pulNumLanguages, StringBuilder pwszLanguagesBuffer, ref uint pcchLanguagesBuffer);

220. GetVersion - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getversion) - No P/Invoke required.

221. GetVersionEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getversionexw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetVersionEx(ref OSVERSIONINFO lpVersionInfo);

222. GetVolumeInformation - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumeinformationw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetVolumeInformation(string lpRootPathName, StringBuilder lpVolumeNameBuffer, uint nVolumeNameSize, out uint lpVolumeSerialNumber, out uint lpMaximumComponentLength, out uint lpFileSystemFlags, StringBuilder lpFileSystemNameBuffer, uint nFileSystemNameSize);

223. GetVolumeNameForVolumeMountPoint - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumenameforvolumemountpointw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetVolumeNameForVolumeMountPoint(string lpszVolumeMountPoint, StringBuilder lpszVolumeName, uint cchBufferLength);

224. GetVolumePathName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumepathnamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetVolumePathName(string lpszFileName, StringBuilder lpszVolumePathName, uint cchBufferLength);

225. GetVolumePathNamesForVolumeName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumepathnamesforvolumenamew) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GetVolumePathNamesForVolumeName(string lpszVolumeName, StringBuilder lpszVolumePathNames, uint cchBufferLength, out uint lpcchReturnLength);

226. GetWindowsDirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getwindowsdirectoryw) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetWindowsDirectory(StringBuilder lpBuffer, uint uSize);

227. GetWriteWatch - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-getwritewatch) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint GetWriteWatch(uint dwFlags, IntPtr lpBaseAddress, uint dwRegionSize, [Out] IntPtr lpAddresses, out uint lpdwCount, out uint lpdwGranularity);

228. GlobalAddAtom - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globaladdatomw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U2)] public static extern ushort GlobalAddAtom(string lpString);

229. GlobalAlloc - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalalloc) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr GlobalAlloc(uint uFlags, UIntPtr dwBytes);

230. GlobalDeleteAtom - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globaldeleteatom) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GlobalDeleteAtom(ushort nAtom);

231. GlobalFindAtom - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalfindatomw) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U2)] public static extern ushort GlobalFindAtom(string lpString);

232. GlobalFree - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalfree) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr GlobalFree(IntPtr hMem);

233. GlobalGetAtomName - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalgetatomnamew) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint GlobalGetAtomName(ushort nAtom, StringBuilder lpBuffer, int nSize);

234. GlobalHandle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalhandle) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr GlobalHandle(IntPtr pMem);

235. GlobalLock - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globallock) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr GlobalLock(IntPtr hMem);

236. GlobalMemoryStatus - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-globalmemorystatus) - No P/Invoke required.

237. GlobalMemoryStatusEx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-globalmemorystatusex) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GlobalMemoryStatusEx(ref MEMORYSTATUSEX lpBuffer);

238. GlobalUnlock - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalunlock) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool GlobalUnlock(IntPtr hMem);

239. Handlerroutine - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/pt-handlerroutine) - No P/Invoke required.

240. Heap32ListFirst - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-heap32listfirst) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Heap32ListFirst(IntPtr hSnapshot, ref HEAPLIST32 lphl);

241. Heap32ListNext - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-heap32listnext) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Heap32ListNext(IntPtr hSnapshot, ref HEAPLIST32 lphl);

242. HeapAlloc - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapalloc) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr HeapAlloc(IntPtr hHeap, uint dwFlags, UIntPtr dwBytes);

243. HeapCreate - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapcreate) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr HeapCreate(uint flOptions, UIntPtr dwInitialSize, UIntPtr dwMaximumSize);

244. HeapDestroy - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapdestroy) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool HeapDestroy(IntPtr hHeap);

245. HeapFree - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapfree) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool HeapFree(IntPtr hHeap, uint dwFlags, IntPtr lpMem);

246. Heapwalk - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapwalk) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool HeapWalk(IntPtr hHeap, ref PROCESS_HEAP_ENTRY lpEntry);

247. Hi - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-hiword) - No P/Invoke required.

248. InitAtomTable - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initatomtable) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool InitAtomTable(uint nSize);

249. InitializeCriticalSection - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-initializecriticalsection) - No P/Invoke required.

250. InitializeCriticalSectionAndSpinCount - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-initializecriticalsectionandspincoun) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool InitializeCriticalSectionAndSpinCount(out CRITICAL_SECTION lpCriticalSection, uint dwSpinCount);

251. InitializeProcThreadAttributeList - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-initializeprocthreadattributelist) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool InitializeProcThreadAttributeList(IntPtr lpAttributeList, int dwAttributeCount, int dwFlags, ref IntPtr lpSize);

252. InterlockedDecrement - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-interlockeddecrement) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.I4)] public static extern int InterlockedDecrement(ref int lpAddend);

253. InterlockedIncrement - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-interlockedincrement) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.I4)] public static extern int InterlockedIncrement(ref int lpAddend);

254. InterlockedOr64 - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-interlockedor64) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U8)] public static extern ulong InterlockedOr64(ref long Destination, long Value);

255. Io_Counters - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/ns-ioapiset-io_counters) - No P/Invoke required.

256. IsBadCodePtr - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-isbadcodeptr) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool IsBadCodePtr(IntPtr lpfn);

257. IsDebuggerPresent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-isdebuggerpresent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool IsDebuggerPresent();

258. IsProcessInJob - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi/nf-jobapi-isprocessinjob) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool IsProcessInJob(IntPtr ProcessHandle, IntPtr JobHandle, out bool Result);

259. IsProcessorFeaturePresent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-isprocessorfeaturepresent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool IsProcessorFeaturePresent(uint ProcessorFeature);

260. IsValidLocale - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-isvalidlocale) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool IsValidLocale(uint Locale, uint dwFlags);

261. IsWow64Process - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-iswow64process) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool IsWow64Process(IntPtr hProcess, out bool Wow64Process);

262. Jobobjectinfoclass - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi2/ns-jobapi2-job_object_info_class) - No P/Invoke required.

263. Jobobjectlimit - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi2/ns-jobapi2-job_object_limit_info) - No P/Invoke required.

264. Jobobject_basic_limit_information - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi/ns-jobapi-jobobject_basic_limit_information) - No P/Invoke required.

265. Jobobject_extended_limit_information - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi2/ns-jobapi2-job_object_extended_limit_info) - No P/Invoke required.

266. Jonas Lehmann - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-jonaslehmann) - No P/Invoke required.

267. L - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-l) - No P/Invoke required.

268. Lcidtoloclename - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-lcidtoloclename) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool LCIDToLocaleName(uint Locale, StringBuilder lpName, int cchName, uint dwFlags);

269. Lcmapstring - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-lcmapstringw) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint LCMapString(uint Locale, uint dwMapFlags, string lpSrcStr, int cchSrc, [Out] StringBuilder lpDestStr, int cchDest);

270. Lcmapstringex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-lcmapstringex) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint LCMapStringEx(string lpLocaleName, uint dwMapFlags, string lpSrcStr, int cchSrc, [Out] StringBuilder lpDestStr, int cchDest, IntPtr lpVersionInformation, IntPtr lpReserved, IntPtr lParam);

271. LeaveCriticalSection - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-leavecriticalsection) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool LeaveCriticalSection(ref CRITICAL_SECTION lpCriticalSection);

272. Lmao - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-lmao) - No P/Invoke required.

273. Loadlibrary - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-loadlibraryw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr LoadLibrary(string lpLibFileName);

274. Loadlibraryex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-loadlibraryexw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr LoadLibraryEx(string lpLibFileName, IntPtr hFile, uint dwFlags);

275. Loadresource - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-loadresource) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr LoadResource(IntPtr hModule, IntPtr hResInfo);

276. Localalloc - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-localalloc) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr LocalAlloc(uint uFlags, UIntPtr uBytes);

277. Localfree - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-localfree) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr LocalFree(IntPtr hMem);

278. Lockfile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-lockfile) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool LockFile(IntPtr hFile, uint dwFileOffsetLow, uint dwFileOffsetHigh, uint nNumberOfBytesToLockLow, uint nNumberOfBytesToLockHigh);

279. Lockfileex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-lockfileex) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool LockFileEx(IntPtr hFile, uint dwFlags, uint dwReserved, uint nNumberOfBytesToLockLow, uint nNumberOfBytesToLockHigh, ref OVERLAPPED lpOverlapped);

280. Lockresource - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-lockresource) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr LockResource(IntPtr hResData);

281. Lstrcat - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-lstrcatw) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr lstrcat(StringBuilder lpString1, string lpString2);

282. Lstrcmp - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-lstrcmpw) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern int lstrcmp(string lpString1, string lpString2);

283. Lstrcpy - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-lstrcpyw) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr lstrcpy(StringBuilder lpString1, string lpString2);

284. Lstrcpyn - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-lstrcpynw) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr lstrcpyn(StringBuilder lpString1, string lpString2, int iMaxLength);

285. Lstrlen - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-lstrlenw) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern int lstrlen(string lpString);

286. Mapuserphysicalpages - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-mapuserphysicalpages) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool MapUserPhysicalPages(IntPtr VirtualAddresses, uint NumberOfPages, IntPtr PageArray);

287. Mapviewoffile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-mapviewoffile) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr MapViewOfFile(IntPtr hFileMappingObject, uint dwDesiredAccess, uint dwFileOffsetHigh, uint dwFileOffsetLow, UIntPtr dwNumberOfBytesToMap);

288. Mdbg - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-mdbg) - No P/Invoke required.

289. Module32first - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-module32first) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Module32First(IntPtr hSnapshot, ref MODULEENTRY32 lpme);

290. Module32next - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-module32next) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Module32Next(IntPtr hSnapshot, ref MODULEENTRY32 lpme);

291. Moduleentry32 - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/ns-tlhelp32-moduleentry32) - No P/Invoke required.

292. Movefile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-movefilew) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool MoveFile(string lpExistingFileName, string lpNewFileName);

293. Movefileex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-movefileexw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool MoveFileEx(string lpExistingFileName, string lpNewFileName, uint dwFlags);

294. Movefilewithprogress - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-movefilewithprogressw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool MoveFileWithProgress(string lpExistingFileName, string lpNewFileName, CopyProgressRoutine lpProgressRoutine, IntPtr lpData, uint dwFlags);

295. Movememory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-movememory) - No P/Invoke required.

296. Multibytetowidechar - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-multibytetowidechar) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern int MultiByteToWideChar(uint CodePage, uint dwFlags, string lpMultiByteStr, int cbMultiByte, [Out] StringBuilder lpWideCharStr, int cchWideChar);

297. Myapplication - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-myapplication) - No P/Invoke required.

298. Nativeoverlapped - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/minwinbase/ns-minwinbase-nativeoverlapped) - No P/Invoke required.

299. Netbios - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/nb30/nf-nb30-netbios) - [DllImport("Netapi32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern NERR Netbios(ref NCB ncb);

300. Nigger - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-nigger) - No P/Invoke required.

301. Not good - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-notgood) - No P/Invoke required.

302. Openevent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-openeventw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenEvent(uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, string lpName);

303. Openfile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-openfile) - [DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenFile(string lpFileName, [Out] OFSTRUCT lpReOpenBuff, uint uStyle);

304. Openfilemapping - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-openfilemappingw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenFileMapping(uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, string lpName);

305. Openmutex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-openmutexw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenMutex(uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, string lpName);

306. Openprocess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openprocess) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenProcess(uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, uint dwProcessId);

307. Opensemaphore - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-opensemaphorew) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenSemaphore(uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, string lpName);

308. Openthread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openthread) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)] public static extern IntPtr OpenThread(uint dwDesiredAccess, [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle, uint dwThreadId);

309. Outputdebugstring - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-outputdebugstringw) - No P/Invoke required.

310. Packagefamilynamefromid - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/msix/package/packagefamilynamefromid) - No P/Invoke required.

311. Packagefullnamefromid - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/msix/package/packagefullnamefromid) - No P/Invoke required.

312. Package_id - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/msix/package/package-id) - No P/Invoke required.

313. Peekconsoleinput - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/peekconsoleinput) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PeekConsoleInput(IntPtr hConsoleInput, [Out] INPUT_RECORD[] lpBuffer, uint nLength, out uint lpNumberOfEventsRead);

314. Peeknamedpipe - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-peeknamedpipe) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PeekNamedPipe(IntPtr hNamedPipe, byte[] lpBuffer, uint nBufferSize, ref uint lpBytesRead, ref uint lpTotalBytesAvail, ref uint lpBytesLeftThisMessage);

315. Platformsdk - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/platformsdk) - No P/Invoke required.

316. Postqueuedcompletionstatus - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-postqueuedcompletionstatus) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PostQueuedCompletionStatus(IntPtr CompletionPort, uint dwNumberOfBytesTransferred, UIntPtr dwCompletionKey, IntPtr lpOverlapped);

317. Process32first - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-process32first) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Process32First(IntPtr hSnapshot, ref PROCESSENTRY32 lppe);

318. Process32next - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-process32next) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Process32Next(IntPtr hSnapshot, ref PROCESSENTRY32 lppe);

319. Processentry32 - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/ns-tlhelp32-processentry32) - No P/Invoke required.

320. Processidtosessionid - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-processidtosessionid) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ProcessIdToSessionId(uint dwProcessId, out uint pSessionId);

321. Processmemorychunk - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-processmemorychunk) - No P/Invoke required.

322. Pulseevent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-pulseevent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PulseEvent(IntPtr hEvent);

323. Purgecomm - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-purgecomm) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PurgeComm(IntPtr hFile, uint dwFlags);

324. Querydosdevice - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-querydosdevice) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint QueryDosDevice(string lpDeviceName, StringBuilder lpTargetPath, uint ucchMax);

325. Queryfullprocessimagename - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-queryfullprocessimagenamea) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryFullProcessImageName(IntPtr hProcess, uint dwFlags, StringBuilder lpExeName, ref uint lpdwSize);

326. Querymemoryresourcenotification - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-querymemoryresourcenotification) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryMemoryResourceNotification(IntPtr ResourceNotificationHandle, out bool ResourceState);

327. Queryperformancecounter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/profileapi/nf-profileapi-queryperformancecounter) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryPerformanceCounter(out long lpPerformanceCount);

328. Queryperformancefrequency - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/profileapi/nf-profileapi-queryperformancefrequency) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryPerformanceFrequency(out long lpFrequency);

329. Queueuserapc - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-queueuserapc) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueueUserAPC(IntPtr pfnAPC, IntPtr hThread, UIntPtr dwData);

330. Readconsole - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsole) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsole(IntPtr hConsoleInput, [Out] StringBuilder lpBuffer, uint nNumberOfCharsToRead, out uint lpNumberOfCharsRead, IntPtr lpReserved);

331. Readconsoleinput - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleinput) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsoleInput(IntPtr hConsoleInput, [Out] INPUT_RECORD[] lpBuffer, uint nLength, out uint lpNumberOfEventsRead);

332. Readconsoleoutput - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleoutput) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsoleOutput(IntPtr hConsoleOutput, [Out] CHAR_INFO[] lpBuffer, COORD dwBufferSize, COORD dwBufferCoord, ref SMALL_RECT lpReadRegion);

333. Readconsoleoutputcharacter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleoutputcharacter) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsoleOutputCharacter(IntPtr hConsoleOutput, [Out] StringBuilder lpCharacter, uint nLength, COORD dwReadCoord, out uint lpNumberOfCharsRead);

334. Readdirectorychangesw - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-readdirectorychangesw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadDirectoryChangesW(IntPtr hDirectory, IntPtr lpBuffer, uint nBufferLength, [MarshalAs(UnmanagedType.Bool)] bool bWatchSubtree, uint dwNotifyFilter, out uint lpBytesReturned, IntPtr lpOverlapped, IntPtr lpCompletionRoutine);

335. Readfile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfile) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadFile(IntPtr hFile, [Out] byte[] lpBuffer, uint nNumberOfBytesToRead, out uint lpNumberOfBytesRead, IntPtr lpOverlapped);

336. Readfileex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfileex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadFileEx(IntPtr hFile, [Out] byte[] lpBuffer, uint nNumberOfBytesToRead, ref OVERLAPPED lpOverlapped, LPOVERLAPPED_COMPLETION_ROUTINE lpCompletionRoutine);

337. Readfilescatter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfilescatter) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadFileScatter(IntPtr hFile, [In] FILE_SEGMENT_ELEMENT[] aSegmentArray, uint nNumberOfBytesToRead, IntPtr lpReserved, ref OVERLAPPED lpOverlapped);

338. Readprocessmemory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-readprocessmemory) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadProcessMemory(IntPtr hProcess, IntPtr lpBaseAddress, [Out] byte[] lpBuffer, uint nSize, out uint lpNumberOfBytesRead);

339. Registerapplicationrestart - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-registerapplicationrestart) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RegisterApplicationRestart(string pwzCommandline, RestartFlags dwFlags);

340. Registerserviceprocess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-registerserviceprocess) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RegisterServiceProcess(uint dwProcessId, uint dwServiceType);

341. Releaseactctx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-releaseactctx) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReleaseActCtx(IntPtr hActCtx);

342. Releasemutex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-releasemutex) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReleaseMutex(IntPtr hMutex);

343. Remotedebugger - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-remotedebugger) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RemoteDebuggerPresent(IntPtr hProcess, [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent);

344. Removedirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-removedirectoryw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RemoveDirectory(string lpPathName);

345. Removelocalalternatecomputername - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-removelocalalternatecomputername) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RemoveLocalAlternateComputerName(string lpAltComName);

346. Reparer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-reparer) - No P/Invoke required.

347. Replacefile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-replacefile) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReplaceFile(string lpReplacedFileName, string lpReplacementFileName, string lpBackupFileName, uint dwReplaceFlags, IntPtr lpExclude, IntPtr lpReserved);

348. Reseteven - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-reseteven) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ResetEvent(IntPtr hEvent);

349. Resumethread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-resumethread) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint ResumeThread(IntPtr hThread);

350. Rtladdfunctiontable - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/rtlapi/nf-rtlapi-rtladdfunctiontable) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RtlAddFunctionTable(ref RUNTIME_FUNCTION FunctionTable, uint EntryCount, uint64 BaseAddress);

351. Safefilehandle - [Microsoft documentation](https://docs.microsoft.com/en-us/dotnet/api/microsoft.win32.safehandles.safefilehandle) - No P/Invoke required.

352. Searchpath - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-searchpathw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint SearchPath(string lpPath, string lpFileName, string lpExtension, uint nBufferLength, [Out] StringBuilder lpBuffer, IntPtr lpFilePart);

353. Securezeromemory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-securezeromemory) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SecureZeroMemory(IntPtr ptr, UIntPtr cnt);

354. Set - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-set) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Set(IntPtr handle);

355. Setcommbreak - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommbreak) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommBreak(IntPtr hFile);

356. Setcommmask - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommmask) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommMask(IntPtr hFile, uint dwEvtMask);

357. Setcommstate - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommstate) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommState(IntPtr hFile, ref DCB lpDCB);

358. Setcommtimeouts - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommtimeouts) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommTimeouts(IntPtr hFile, ref COMMTIMEOUTS lpCommTimeouts);

359. Setcomputername - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcomputernamea) - [DllImport("Kernel32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetComputerName(string lpComputerName);

360. Setcomputernameex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcomputernameexw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetComputerNameEx(COMPUTER_NAME_FORMAT NameType, string lpBuffer);

361. Setconsoleactivescreenbuffer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincon/nf-wincon-setconsoleactivescreenbuffer) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleActiveScreenBuffer(IntPtr hConsoleOutput);

312. Package_id - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/msix/package/package-id) - No P/Invoke required.

313. Peekconsoleinput - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/peekconsoleinput) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PeekConsoleInput(IntPtr hConsoleInput, [Out] INPUT_RECORD[] lpBuffer, uint nLength, out uint lpNumberOfEventsRead);

314. Peeknamedpipe - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-peeknamedpipe) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PeekNamedPipe(IntPtr hNamedPipe, byte[] lpBuffer, uint nBufferSize, ref uint lpBytesRead, ref uint lpTotalBytesAvail, ref uint lpBytesLeftThisMessage);

315. Platformsdk - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/platformsdk) - No P/Invoke required.

316. Postqueuedcompletionstatus - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-postqueuedcompletionstatus) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PostQueuedCompletionStatus(IntPtr CompletionPort, uint dwNumberOfBytesTransferred, UIntPtr dwCompletionKey, IntPtr lpOverlapped);

317. Process32first - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-process32first) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Process32First(IntPtr hSnapshot, ref PROCESSENTRY32 lppe);

318. Process32next - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-process32next) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Process32Next(IntPtr hSnapshot, ref PROCESSENTRY32 lppe);

319. Processentry32 - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/ns-tlhelp32-processentry32) - No P/Invoke required.

320. Processidtosessionid - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-processidtosessionid) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ProcessIdToSessionId(uint dwProcessId, out uint pSessionId);

321. Processmemorychunk - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-processmemorychunk) - No P/Invoke required.

322. Pulseevent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-pulseevent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PulseEvent(IntPtr hEvent);

323. Purgecomm - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-purgecomm) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool PurgeComm(IntPtr hFile, uint dwFlags);

324. Querydosdevice - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-querydosdevice) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint QueryDosDevice(string lpDeviceName, StringBuilder lpTargetPath, uint ucchMax);

325. Queryfullprocessimagename - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-queryfullprocessimagenamea) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryFullProcessImageName(IntPtr hProcess, uint dwFlags, StringBuilder lpExeName, ref uint lpdwSize);

326. Querymemoryresourcenotification - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-querymemoryresourcenotification) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryMemoryResourceNotification(IntPtr ResourceNotificationHandle, out bool ResourceState);

327. Queryperformancecounter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/profileapi/nf-profileapi-queryperformancecounter) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryPerformanceCounter(out long lpPerformanceCount);

328. Queryperformancefrequency - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/profileapi/nf-profileapi-queryperformancefrequency) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueryPerformanceFrequency(out long lpFrequency);

329. Queueuserapc - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-queueuserapc) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool QueueUserAPC(IntPtr pfnAPC, IntPtr hThread, UIntPtr dwData);

330. Readconsole - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsole) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsole(IntPtr hConsoleInput, [Out] StringBuilder lpBuffer, uint nNumberOfCharsToRead, out uint lpNumberOfCharsRead, IntPtr lpReserved);

331. Readconsoleinput - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleinput) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsoleInput(IntPtr hConsoleInput, [Out] INPUT_RECORD[] lpBuffer, uint nLength, out uint lpNumberOfEventsRead);

332. Readconsoleoutput - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleoutput) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsoleOutput(IntPtr hConsoleOutput, [Out] CHAR_INFO[] lpBuffer, COORD dwBufferSize, COORD dwBufferCoord, ref SMALL_RECT lpReadRegion);

333. Readconsoleoutputcharacter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleoutputcharacter) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadConsoleOutputCharacter(IntPtr hConsoleOutput, [Out] StringBuilder lpCharacter, uint nLength, COORD dwReadCoord, out uint lpNumberOfCharsRead);

334. Readdirectorychangesw - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-readdirectorychangesw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadDirectoryChangesW(IntPtr hDirectory, IntPtr lpBuffer, uint nBufferLength, [MarshalAs(UnmanagedType.Bool)] bool bWatchSubtree, uint dwNotifyFilter, out uint lpBytesReturned, IntPtr lpOverlapped, IntPtr lpCompletionRoutine);

335. Readfile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfile) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadFile(IntPtr hFile, [Out] byte[] lpBuffer, uint nNumberOfBytesToRead, out uint lpNumberOfBytesRead, IntPtr lpOverlapped);

336. Readfileex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfileex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadFileEx(IntPtr hFile, [Out] byte[] lpBuffer, uint nNumberOfBytesToRead, ref OVERLAPPED lpOverlapped, LPOVERLAPPED_COMPLETION_ROUTINE lpCompletionRoutine);

337. Readfilescatter - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfilescatter) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadFileScatter(IntPtr hFile, [In] FILE_SEGMENT_ELEMENT[] aSegmentArray, uint nNumberOfBytesToRead, IntPtr lpReserved, ref OVERLAPPED lpOverlapped);

338. Readprocessmemory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-readprocessmemory) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReadProcessMemory(IntPtr hProcess, IntPtr lpBaseAddress, [Out] byte[] lpBuffer, uint nSize, out uint lpNumberOfBytesRead);

339. Registerapplicationrestart - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-registerapplicationrestart) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RegisterApplicationRestart(string pwzCommandline, RestartFlags dwFlags);

340. Registerserviceprocess - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-registerserviceprocess) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RegisterServiceProcess(uint dwProcessId, uint dwServiceType);

341. Releaseactctx - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-releaseactctx) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReleaseActCtx(IntPtr hActCtx);

342. Releasemutex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-releasemutex) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReleaseMutex(IntPtr hMutex);

343. Remotedebugger - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-remotedebugger) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RemoteDebuggerPresent(IntPtr hProcess, [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent);

344. Removedirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-removedirectoryw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RemoveDirectory(string lpPathName);

345. Removelocalalternatecomputername - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-removelocalalternatecomputername) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RemoveLocalAlternateComputerName(string lpAltComName);

346. Reparer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-reparer) - No P/Invoke required.

347. Replacefile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-replacefile) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ReplaceFile(string lpReplacedFileName, string lpReplacementFileName, string lpBackupFileName, uint dwReplaceFlags, IntPtr lpExclude, IntPtr lpReserved);

348. Reseteven - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-reseteven) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool ResetEvent(IntPtr hEvent);

349. Resumethread - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-resumethread) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)] public static extern uint ResumeThread(IntPtr hThread);

350. Rtladdfunctiontable - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/rtlapi/nf-rtlapi-rtladdfunctiontable) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool RtlAddFunctionTable(ref RUNTIME_FUNCTION FunctionTable, uint EntryCount, uint64 BaseAddress);

351. Safefilehandle - [Microsoft documentation](https://docs.microsoft.com/en-us/dotnet/api/microsoft.win32.safehandles.safefilehandle) - No P/Invoke required.

352. Searchpath - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-searchpathw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)] public static extern uint SearchPath(string lpPath, string lpFileName, string lpExtension, uint nBufferLength, [Out] StringBuilder lpBuffer, IntPtr lpFilePart);

353. Securezeromemory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-securezeromemory) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SecureZeroMemory(IntPtr ptr, UIntPtr cnt);

354. Set - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-set) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool Set(IntPtr handle);

355. Setcommbreak - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommbreak) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommBreak(IntPtr hFile);

356. Setcommmask - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommmask) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommMask(IntPtr hFile, uint dwEvtMask);

357. Setcommstate - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommstate) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommState(IntPtr hFile, ref DCB lpDCB);

358. Setcommtimeouts - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcommtimeouts) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCommTimeouts(IntPtr hFile, ref COMMTIMEOUTS lpCommTimeouts);

359. Setcomputername - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcomputernamea) - [DllImport("Kernel32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetComputerName(string lpComputerName);

360. Setcomputernameex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcomputernameexw) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetComputerNameEx(COMPUTER_NAME_FORMAT NameType, string lpBuffer);

361. Setconsoleactivescreenbuffer - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincon/nf-wincon-setconsoleactivescreenbuffer) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleActiveScreenBuffer(IntPtr hConsoleOutput);

362. Setconsolectrlhandler - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolectrlhandler) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleCtrlHandler(ConsoleCtrlHandlerRoutine HandlerRoutine, bool Add);

363. Setconsolefont - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolefont) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleFont(IntPtr hConsoleOutput, uint dwFontIndex);

364. Setconsolehistoryinfo - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolehistoryinfo) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleHistoryInfo(ref CONSOLE_HISTORY_INFO ConsoleHistoryInfo);

365. Setconsoleicon - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsoleicon) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleIcon(IntPtr hIcon);

366. Setconsolemode - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolemode) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleMode(IntPtr hConsoleHandle, uint dwMode);

367. Setconsolescreenbufferinfoex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolescreenbufferinfoex) - [DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleScreenBufferInfoEx(IntPtr hConsoleOutput, ref CONSOLE_SCREEN_BUFFER_INFO_EX lpConsoleScreenBufferInfoEx);

368. Setconsoletitle - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsoletitle) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetConsoleTitle(string lpConsoleTitle);

369. Setcriticalsectionspincount - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-setcriticalsectionspincount) - No P/Invoke required.

370. Setcurrentconsolefontex - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setcurrentconsolefontex) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCurrentConsoleFontEx(IntPtr hConsoleOutput, bool bMaximumWindow, ref CONSOLE_FONT_INFO_EX lpConsoleCurrentFontEx);

371. Setcurrentdirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcurrentdirectory) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetCurrentDirectory(string lpPathName);

372. Setdefaultdlldirectories - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-setdefaultdlldirectories) - No P/Invoke required.

373. Setdlldirectory - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-setdlldirectory) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetDllDirectory(string lpPathName);

374. Setdynamictimezoneinformation - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-setdynamictimezoneinformation) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetDynamicTimeZoneInformation([In] ref DYNAMIC_TIME_ZONE_INFORMATION lpTimeZoneInformation);

375. Setendoffile - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setendoffile) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetEndOfFile(IntPtr hFile);

376. Setenvironmentvariable - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setenvironmentvariable) - [DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetEnvironmentVariable(string lpName, string lpValue);

377. Seterrormode - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-seterrormode) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern uint SetErrorMode(uint uMode);

378. Setevent - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-setevent) - [DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetEvent(IntPtr hEvent);

379. Setfileapistoansi - [Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setfileapistooem) - [DllImport("Kernel32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)] public static extern bool SetFileAPIToANSI();

