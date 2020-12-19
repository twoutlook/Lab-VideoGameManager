# Lab-VideoGameManager 


---

C# ASP.NET Core 5 with Entity Framework 5 - The Fundamentals (Part 1)
Dec 17, 2020
https://youtu.be/ntduhJkQLe4

---

C# ASP.NET Core 5 with Entity Framework 5 - The Fundamentals (Part 2)
Dec 17, 2020
https://youtu.be/C6sXxTaTff8

---

C# ASP.NET Core 5 with Entity Framework 5 - The Fundamentals (Part 3)
Dec 17, 2020
https://youtu.be/bCnbhB1Yo7Q

---

[Part1 11:33]
1. run on VideoGameManager as console app, not IIS Express
   - on VideoGameManager properties debug
    Profile IIS Express to Delete

2. RUN and check CMD windows and popup Explorer
  - port 5000 and 5001 for https


  ```

  2020-12-19, 06:09:52.743 UTC
[06:09:52.743 UTC] OS: win32 x64
[06:09:52.743 UTC] Adapter node: v12.16.3 x64
[06:09:52.743 UTC] vscode-chrome-debug-core: 6.7.50
[06:09:52.743 UTC] debugger-for-edge: 1.0.15
[06:09:52.743 UTC] From client: initialize({"pathFormat":"path","clientID":"visualstudio","clientName":"Visual Studio","adapterID":"edge","locale":"en-US","linesStartAt1":true,"columnsStartAt1":true,"supportsVariableType":true,"supportsRunInTerminalRequest":true,"supportsMemoryReferences":true,"supportsProgressReporting":true,"SupportsMessageBox":true,"supportsHandshakeRequest":true,"supportsVsAdditionalBreakpointBinds":true,"supportsHitCountsChange":true,"supportsVsCustomMessages":true,"supportsMapURLToFilePathRequest":true,"supportsLaunchUnelevatedProcessRequest":true})
[06:09:52.743 UTC] To client: {"seq":0,"type":"response","request_seq":1,"command":"initialize","success":true,"body":{"exceptionBreakpointFilters":[{"label":"All Exceptions","filter":"all","default":false},{"label":"Uncaught Exceptions","filter":"uncaught","default":false}],"supportsConfigurationDoneRequest":true,"supportsSetVariable":true,"supportsConditionalBreakpoints":true,"supportsCompletionsRequest":true,"supportsHitConditionalBreakpoints":true,"supportsRestartFrame":true,"supportsExceptionInfoRequest":true,"supportsDelayedStackTraceLoading":true,"supportsValueFormattingOptions":true,"supportsEvaluateForHovers":true,"supportsLoadedSourcesRequest":true,"supportsRestartRequest":true,"supportsSetExpression":true,"supportsLogPoints":true}}
[06:09:52.743 UTC] To client: {"seq":0,"type":"event","event":"output","body":{"category":"telemetry","output":"ClientRequest/initialize","data":{"Versions.DebugAdapterCore":"6.7.50","Versions.DebugAdapter":"1.0.15","successful":"true","timeTakenInMilliseconds":"3.406401","requestType":"request"}}}
[06:09:52.743 UTC] From client: launch({"name":"Attach to Edge program from Visual Studio","type":"edge","request":"launch","breakOnLoad":true,"breakOnLoadStrategy":"instrument","_clientOverlayPausedMessage":"Paused in Visual Studio","logFilePath":"C:\\Users\\user\\AppData\\Local\\Temp\\visualstudio-js-debugger.txt","trace":"info","sourceMaps":true,"showAsyncStacks":true,"smartStep":false,"url":"https://localhost:5001/swagger","runtimeExecutable":"C:\\Program Files (x86)\\Microsoft\\Edge\\Application\\msedge.exe","userDataDir":"C:\\Users\\user\\AppData\\Local\\Microsoft\\VisualStudio\\16.0_95d9a107\\WebTools\\F17440DA_679C4B14","webRoot":"D:\\DEV\\daily\\EFCore\\Rainer Stropek\\VideoGameManager","port":59799})
[06:09:52.743 UTC] To client: {"seq":0,"type":"event","event":"output","body":{"category":"telemetry","output":"debugStarted","data":{"Versions.DebugAdapterCore":"6.7.50","Versions.DebugAdapter":"1.0.15","request":"launch","args":["name","type","request","breakOnLoad","breakOnLoadStrategy","_clientOverlayPausedMessage","logFilePath","trace","sourceMaps","showAsyncStacks","smartStep","url","runtimeExecutable","userDataDir","webRoot","port","pathMapping","sourceMapPathOverrides","skipFileRegExps","targetFilter"]}}}
[06:09:52.743 UTC] spawn('C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe', ["--remote-debugging-port=59799","--no-first-run","--no-default-browser-check","--user-data-dir=C:\\Users\\user\\AppData\\Local\\Microsoft\\VisualStudio\\16.0_95d9a107\\WebTools\\F17440DA_679C4B14","about:blank"])
[06:09:52.743 UTC] Getting browser and debug protocol version via http://127.0.0.1:59799/json/version
[06:09:52.743 UTC] Discovering targets via http://127.0.0.1:59799/json/list
[06:09:54.746 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:09:54.746 UTC] There was an error connecting to http://127.0.0.1:59799/json/version : connect ECONNREFUSED 127.0.0.1:59799
[06:09:54.747 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:09:54.747 UTC] Discovering targets via http://127.0.0.1:59799/json
[06:09:56.748 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:09:56.949 UTC] Getting browser and debug protocol version via http://127.0.0.1:59799/json/version
[06:09:56.949 UTC] Discovering targets via http://127.0.0.1:59799/json/list
[06:09:58.954 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:09:58.954 UTC] Discovering targets via http://127.0.0.1:59799/json
[06:09:58.954 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:09:58.955 UTC] There was an error connecting to http://127.0.0.1:59799/json/version : connect ECONNREFUSED 127.0.0.1:59799
[06:10:00.957 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:10:01.157 UTC] Getting browser and debug protocol version via http://127.0.0.1:59799/json/version
[06:10:01.157 UTC] Discovering targets via http://127.0.0.1:59799/json/list
[06:10:03.160 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:10:03.160 UTC] Discovering targets via http://127.0.0.1:59799/json
[06:10:03.161 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:10:03.161 UTC] There was an error connecting to http://127.0.0.1:59799/json/version : connect ECONNREFUSED 127.0.0.1:59799
[06:10:05.162 UTC] HTTP GET failed: Error: connect ECONNREFUSED 127.0.0.1:59799
[06:10:05.163 UTC] To client: {"seq":0,"type":"event","event":"output","body":{"category":"telemetry","output":"ClientRequest/launch","data":{"Versions.DebugAdapterCore":"6.7.50","Versions.DebugAdapter":"1.0.15","successful":"false","exceptionType":"firstChance","exceptionMessage":"Cannot connect to runtime process, timeout after {_timeout} ms - (reason: {_error}).","exceptionName":"Error","exceptionStack":"Error: Cannot connect to runtime process, timeout after {_timeout} ms - (reason: {_error}).\n    at Object.runtimeConnectionTimeout (errors.js:91:12)\n    at chromeConnection.js:110:49\n    at processTicksAndRejections (internal/process/task_queues.js:97:5)","exceptionId":"2010","timeTakenInMilliseconds":"12447.623101","requestType":"request","doesHostSupportLaunchUnelevated":"true","numberOfEdgeCmdLineSwitchesBeingUsed":"0"}}}
[06:10:05.164 UTC] To client: {"seq":0,"type":"response","request_seq":2,"command":"launch","success":false,"message":"Cannot connect to runtime process, timeout after 10000 ms - (reason: Cannot connect to the target: connect ECONNREFUSED 127.0.0.1:59799).","body":{"error":{"id":2010,"format":"Cannot connect to runtime process, timeout after {_timeout} ms - (reason: {_error}).","variables":{"_error":"Cannot connect to the target: connect ECONNREFUSED 127.0.0.1:59799","_timeout":"10000"}}}}

```


-- https://stackoverflow.com/questions/36783068/cannot-connect-to-the-target-connect-econnrefused-127-0-0-19222/36845875

-- change another browser works!




