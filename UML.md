

**User**

\- userName : String

\- password : String

\- name : String

\- Age : int

\- Email : String

\+ totalParents : int

**AppBlock**

**StudyMaterial**

\- title: String

\- description: String

\- dateCreated: Date

\- type: String

\- blockedApps: List<String>

\+ blockApp(appName: String)

\+ unblockApp(appName: String)

\+ isAppBlocked(appName : String

\- rating: int

\+ setAge( Age : int)

\+ setName(name : String)

\+ getUserName(userName : String)

\+ getPassword(password : String)

\+ getSchedule()

\+ getProgress()

\+ getAppBlock()

\+ enableParentMode()

\+ setParent()

+setTotalParents()

\+ setTitle(title: String)

\+ getTitle(): String

\+ setDescription(description:String)

\+ getDescription(): String

\+ setDateCreated(date: Date)

\+ getDateCreated()

\+ setType()

1 .. \*

1 .. \*

Uses

**Timer**

\- remainingTime : int

has a

\+ startTime()

\+ stopTime()

\+ timeDiff()

\+ getRemainingTime()

\+ getType()

\+ setRating(rating: int)

Child of

\+ getRating(): int

\+ sortByRating()

0\..\*

\+ sortByDate()

\+ sortBySize()

**Parent**

\- userName : String

\- password : String

make/view

has a

\+ seUsername(username: String)

\+ sePassword(password: String)

\+ getLinkedUser()

**Quiz**

**Assessment**

\+ setLinkedUser()

\+ getProgress : Progress

\- title: String

\- questions: List<Question>

\- questions: List<Question>

\- timeLimit: int

\- duration: int

\- difficulty: String

\- dateCreated: Date

\- difficulty: String

\- topic: String

\- instructions: String

**Schedule**

\+ Tasks: List <Task>

\+ getTask()

\+ addTask()

\+ deleteTask()

\+ editTask()

\+ getQuestions(): List<Question>

\+ getTimeLimit(): int

\+ getDifficulty(): String

\+ getTopic(): String

\+ setTitle(title: String)

\+ getTitle(): String

\+ setQuestions(questions: List<Question>)

\+ getQuestions(): List<Question>

\+ addQuestion(question: Question)

\+ removeQuestion(question: Question)

\+ setDuration(duration: int)

\+ getDuration(): int

\+ setDifficulty()

\+ getDifficulty()

\+ setDateCreated(date:Date)

\+ getDateCreated(): Date

can view

\+ getInstructions()

contains

contains

**Question**

**Task**

1\..1

**Progress**

\- questionText: String

\- choices: List<String>

\- correctAnswer: String

\- explanation: String

\- name: String

\- description: String

\- startDate: Date

\- endDate: Date

\- level: int

\- score : int

\- timeSpent : int

\+ getName(): String

\+ getDescription()

\+ getStartDate()

\+ getEndDate()

\+ getQuestionText(): String

\+ getChoices(): List<String>

\+ getCorrectAnswer()

\+ setLevel(level : int)

\+ getScore()

\+ getLevel()

\+ getExplanation()

\+ setScore()

