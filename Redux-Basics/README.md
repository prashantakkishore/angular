# Redux-Basics

## Setup

Run `npm install` to get required JS libraries.

THis is having redux basics staring concept from plain Javascript. This is having 2 JS to explain the same.

### app.js

The 'addView' method will display the state that was first assigned and if we change the cources, it wont display new state or modified data.

### finalApp.js

This is where Redux comes in , here is the flow.

1. Create redux `store` with `reducer` and `defaultState`. `reducer` takes actions and performs data massaging and returns new state.

2. Change in state happens through `dispatch` , which calls `reducer`.

3. View will do `store.subscribe` to get notified of new state.

![Alt text](images/redux_basics.png?raw=true "Redux Flow")

