# React Review 1

## Answer 1 Create a Simple Component

```js
function Intro() {
    return <h1>Intro to React!</h1>;
}
```

## Answer 2 Create a Bigger Component

```js
function Ciao() {
return (
<>
<p>Ciao</p>
<p>Mundo</p>
</div>
</>
);
}
```

## Answer 3 Create an Image Component

```js
function LoginButton() {
return (
<>
<div>
<img src='../assets/images/profile-picture.jpg' />
<button>Sign out</button>
</div>
</>
);
}
```

## Answer 4 Create a Component that Uses Variables

```js

function User() {
  const username = "john_doe";
  const xp = 737451;
  return (
    <>
    <div>{username}</div>
    <div>{xp}</div>
    <>
  );
}

// Write your code here
```

## Answer 5 Is the Code Correct? Components

```
The FoodList component will render an h1 "Bananas", and then three lists that each say "1. Green Banana"
```

## Answer 6 Export a Component

```js
// Modify the code below

import React from 'react';

const ChapterList = () => {
  return (
    <div>
      <h2>Table of Contents</h2>
      <ul>
        <li>Introduction to Biking</li>
        <li>Chapter 1: Choosing the Right Bike</li>
        <li>Chapter 2: Essential Bike Gear</li>
        <li>Chapter 3: Basic Riding Techniques</li>
        <li>Chapter 4: Maintaining Your Bike</li>
        <li>Conclusion: Enjoying Your Ride</li>
      </ul>
    </div>
  );
};

export default ChapterList;
```

## Answer 7 Import a Component

```js
// This is the App.jsx file

import Gallery from './components/Gallery.jsx';

function App() {
  return (
    <div>
      <Gallery></Gallery>
    </div>
  );
}

export default App;
```

## Answer 8 Is the Code Correct? JSX

## Answer 9 Fix the JSX Bugs

```js
// Modify the code below

const Summary = () => {
  return (
    <div className="Title">
      <h1>My Site!</h1>
    </div>
    <p className="Description">
      You can find my thoughts here
      <br>
      <b>And <i>I</b></i> have plenty of them!
    </p>
  );
}
```

## Answer 10 Create a Component with a Prop

```js
// Out of time
```

## Answer 11 Pass a Prop to a Component

```js
const App = () => {
  // Out of time
};
```

## Answer 12 Denise's chat

```
Don't use a password manager
```


