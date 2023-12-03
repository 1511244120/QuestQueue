# QuestQueue
QuestQueue is a powerful and intuitive to-do list application built using React Native. It offers a seamless and efficient way to manage your tasks, whether they're daily errands, work-related assignments, or personal goals. With QuestQueue, you can easily add new tasks, mark them as completed, and remove tasks that are no longer needed.

## How to run the project

**Clone the repository to your local computer:**
``` bash
$ git clone https://github.com/1511244120/QuestQueue.git
```
**Change to the project:**
``` bash
$ cd QuestQueue
```
**Install the dependencies:**
``` bash
$ npm install
```
**Start the project:**
``` bash
$ npm start
```
Then test the project out, happy coding!

---
some notes when using react with best practice:<br>
parent-child component communication: 
- parent -> child using props
- child -> parent using state, put inside parent's state, required a function to pass to child in advance

- if information is only used by one component, put it inside that component's state
- if information is shared by multiple states, put it inside their shared parent's state

- defaultChecked on executed at the first time
- state and the method to operate the state should be at the same place
某一个组件使用，放在自身的state中
某些组件使用，放在他们共同的父组件state种

父组件之间通信：
父组件给子组件传递数据：通过props
子组件给父组件传递数据：通过props, 要求提前给子组件传递一个函数

defaultChecked只有在第一次执行起作用

状态在哪里操作状态的方法就在哪里
