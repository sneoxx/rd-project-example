### Example project for courses

В данном проекте представлена структура проекта, которой все должны придерживаться.

* src
	* main
		* java
			* *фамилия*
				* *ваши пакеты*
					* Main.class
		* resources
			* file.txt 
	* test
		* java
			* *фамилия*
				* *ваши пакеты*
					* MainTest.class
* .gitignore
* pom.xml

, где 
* *фамилия* - ваша фамилия
* *ваши пакеты* - последующие пакеты на ваше усмотрение
* *.gitignore* - можно копипаст себе
* *pom.xml* - maven файл, который на старте **не нужен**
* *.github* - на старте **не нужен**

### Workflow сдачи заданий

Для начала необходимо добавить всех преподавателей в коллабораторы вашего проекта. [Инструкция.](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository "Инструкция")
Если слабо владеете git, пройдите начальные уроки [здесь](https://learngitbranching.js.org/ "здесь").

Во время выполнения заданий проходите следующие шаги:
1. При старте нового задания ответвляетесь от **master** ветки с названием урока. Например: **lesson1**
2. Перед началом написания нового кода ответвляетесь от новосозданной ветки на попытку выполнения. Например: **lesson1-try1**. Где номер на конце - номер попытки сдачи задания.
3. Пишите код и пушите его в новую ветку.
4. Далее на github делаете pull-request из ветки **lesson1-try1** в ветку **lesson1**. [Инструкция](https://help.github.com/en/desktop/contributing-to-projects/creating-a-pull-request "Инструкция")
5. Асайните этот pull-requst на преподавателя. [Инструкция](https://help.github.com/en/github/managing-your-work-on-github/assigning-issues-and-pull-requests-to-other-github-users "Инструкция") 
    1. Желательно скинуть ссылку на pull-request нам в общий чат.
6. Ждёте проверки выполнения.
    1. Если успешно, то вы молодец и приступатее к выполнению нового задания с шага 1. 
        1. Преподаватель смержит ваше выполнение в репозиторий. (Не делайте этого сами)
    2. Если безуспешно, то рано отчаиваться и редактируете код согласно оставленным комментариям в ветке **lesson1-try1**. И делаете новые коммиты. 
        1. Преподаватель же оставит комментарии. Если он поймет, что вы делаете неправильно, то отклонит пул реквест и вы продолжаете заново с шага 4.
