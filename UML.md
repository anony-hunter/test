|**StudyMaterial**|
| - |
|<p>- title: String   </p><p>- description: String</p><p>- dateCreated: Date</p><p>- type: String</p><p>- rating: int </p>|
|<p>+ setTitle(title: String)</p><p>+ getTitle(): String</p><p>+ setDescription(description:String) </p><p>+ getDescription(): String</p><p>+ setDateCreated(date: Date)</p><p>+ getDateCreated()</p><p>+ setType()</p><p>+ getType()</p><p>+ setRating(rating: int)</p><p>+ getRating(): int</p><p>+ sortByRating()</p><p>+ sortByDate()</p><p>+ sortBySize()</p>|

|**Quiz**|
| - |
|<p>- title: String  </p><p>- questions: List<Question> </p><p>- duration: int   </p><p>- difficulty: String </p><p>- dateCreated: Date</p>|
|<p>+ setTitle(title: String)</p><p>+ getTitle(): String</p><p>+ setQuestions(questions: List<Question>)</p><p>+ getQuestions(): List<Question></p><p>+ addQuestion(question: Question) </p><p>+ removeQuestion(question: Question)</p><p>+ setDuration(duration: int)</p><p>+ getDuration(): int</p><p>+ setDifficulty()</p><p>+ getDifficulty()</p><p>+ setDateCreated(date:Date)</p><p>+ getDateCreated(): Date</p>|

|**Parent**|
| - |
|<p>- userName : String</p><p>- password : String </p>|
|<p>+ seUsername(username: String)    </p><p>+ sePassword(password: String)</p><p>+ getLinkedUser()          </p><p>+ setLinkedUser()</p><p>+ getProgress : Progress</p>|


|**User**|
| - |
|<p>- userName : String</p><p>- password : String</p><p>- name : String</p><p>- Age : int</p><p>- Email : String</p><p>+ totalParents : int</p>|
|<p>+ setAge( Age : int)</p><p>+ setName(name : String)</p><p>+ getUserName(userName : String)</p><p>+ getPassword(password : String)</p><p>+ getSchedule()</p><p>+ getProgress()</p><p>+ getAppBlock()</p><p>+ enableParentMode()</p><p>+ setParent()</p><p>+ getRemainingTime()</p>|

|**Timer**|
| - |
|- remainingTime : int|
|<p>+ startTime()</p><p>+ stopTime()</p><p>+ timeDiff()</p>|

|**Assessment**|
| - |
|<p>- questions: List<Question></p><p>- timeLimit: int</p><p>- difficulty: String</p><p>- topic: String</p><p>- instructions: String</p>|
|<p>+ getQuestions(): List<Question> </p><p>+ getTimeLimit(): int </p><p>+ getDifficulty(): String </p><p>+ getTopic(): String </p><p>+ getInstructions()</p>|

|**Progress**|
| - |
|<p>- level: int</p><p>- score : int</p><p>- timeSpent : int</p>|
|<p>+ setLevel(level : int)</p><p>+ getScore()</p><p>+ getLevel()</p><p>+ setScore()</p>|

|**AppBlock**|
| - |
|- blockedApps: List<String>|
|<p>+ blockApp(appName: String)</p><p>+ unblockApp(appName: String)</p><p>+ isAppBlocked(appName : String</p>|

|**Task**|
| - |
|<p>- name: String      </p><p>- description: String </p><p>- startDate: Date   </p><p>- endDate: Date  </p>|
|<p>+ getName(): String </p><p>+ getDescription()</p><p>+ getStartDate()</p><p>+ getEndDate()</p>|

|**Question**|
| - |
|<p>- questionText: String </p><p>- choices: List<String> </p><p>- correctAnswer: String </p><p>- explanation: String</p>|
|<p>+ getQuestionText(): String </p><p>+ getChoices(): List<String> </p><p>+ getCorrectAnswer() </p><p>+ getExplanation()</p>|

|**Schedule**|
| - |
|+ Tasks: List <Task>|
|<p>+ getTask()</p><p>+ addTask()</p><p>+ deleteTask()</p><p>+ editTask()</p>|

