# [Habit Tracker](https://sery-habit-tracker.netlify.app/)

It tracks your habit!

## Features

Users are able to

- add new habit
- delete a habit
- see the list of habits
- see & control the frequency of habit

## What I Learn

- [x] create react-app
- [x] JSX
- [x] Class Component
- [x] Function Component
- [x] Lifecycle methods
- [x] React Hook
- [x] Pure Component
- [x] memo(Higher Order Component)
- [x] synthetic event
- [x] state & Props
- [x] Refs
- [x] setState
- [x] useEffect

## Note ✍🏻

### Reason you should not change State directly

- Changing object directly causes unexpected error, so that
  the object already exists should be immutable
- setState is asynchronous
- PureComponent do a shallow comparison

### To prevent enroll empty string use trim()

```js
  if (name.trim() === '') {
      formRef.current.reset();
      return;
    }
```

## Setup

Install dependencies
```sh
$ npm install
```

Run application
```sh
$ npm start
```
