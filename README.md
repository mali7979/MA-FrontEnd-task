TODO List App

Component Hierarchy
Home
TODOList
Todos
TodoItem

Home ⇒ Main Component
		App starts from here and it renders ToDoList component

ToDoList ⇒ Show All Todos
		Main Logic Here
		It render todos component
		All Edit, complete and delete logic wrote here

Todos ⇒ Map todos to TodoItem component
		Contain map loop

TodoItem ⇒ Single TodoItem
Single todo item render here


How to start App?
Clone https://github.com/mali7979/MA-FrontEnd-task  github repo
Go to directory and run npm install
After run `npm run dev`
Then goto localhost:3000/
Your app is running

All Code is commented so just go through it.
