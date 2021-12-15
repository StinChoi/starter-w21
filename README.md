# README

# Starter Project Winter 2021

This project is meant to be a starter for homework/projects.
It is Rails 6 API app with React frontend

# Setup

### Libraries
- devise_token_auth
- React (v )
- react-router (v6)
- Rails ( 6.1.4 )

### React Router Setup

install react-router-dom
```
$ yarn add react-router-dom
```

setup index.js
```javascript
import { BrowserRouter } from "react-router-dom";

ReactDOM.render(
  <BrowserRouter>
    <App />
  </BrowserRouter>,
  document.getElementById('root')
);
```
add Routes in App.js
```javascript
import { Routes, Route } from 'react-router-dom';

function App() {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/public" element={<Public />} />
      <Route path="/protected" element={<Protected />} />
    </Routes>
  );
}

export default App;


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
