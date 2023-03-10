

|**User**|
| - |
|<p>- userName : String</p><p>- password : String</p><p>- name : String + </p><p>- Age : int</p><p>- Email : String</p>|
|<p>+ setAge( Age : int)</p><p>+ setName(name : String)</p><p>+ getUserName(userName : String)</p><p>+ getPassword(password : String)</p><p>+ getSchedule : Schedule</p><p>+ getProgress : Progress</p><p>+ getAppBlock : AppBlock</p><p>+ enableParentMode()</p><p>+ setParent : Parent</p>|

|**Parent**|
| - |
|-UserName : String -Password : String |
|<p>+ setUsername(username: String)    </p><p>+ setPassword(password: String)</p><p>+ getLinkedUser()          </p><p>+ setLinkedUser(user: User)</p><p>+ getProgress : Progress</p>|


|**Progress**|
| - |
|<p>+ level: int</p><p>+ score : int</p><p>+ timeSpent : int</p>|
|<p>+ setLevel(level : int)</p><p>+ getScore()</p>|
**VisualTimer**

+ remainingTime : int
+ start()
+ stop()

|**AppBlock**|
| - |
|- blockedApps: List<String>|
|<p>+ blockApp(appName: String)</p><p>+ unblockApp(appName: String)</p><p>+ isAppBlocked(appName : String</p>|

|**Schedule**|
| - |
|+ timetable: List <String>|
|<p>+ setSchedule: (Tasks : List <String>)</p><p>+ addTask()</p><p>+ deleteTask()</p>|

