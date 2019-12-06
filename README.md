## IPut

### About
一个简单的IP输入框组件

ip input component for react(>=0.14).

### Usage
### install
`npm install https://github.com/UlyC/iput.git --save`

#### basic Usage

```javascript
  import React from 'react';
  import ReactDOM from 'react-dom';
  import IPut from 'iput';

  ReactDOM.render(
    <IPut />,
    document.getElementById('app')
  );
```

### API

#### IPut props

| name         | type                    | default | description                           |
| ------------ | ----------------------- | ------- | ------------------------------------- |
| className    | String                  |         | additional css class of root dom node |
| defaultValue | String\|Array\<String\> |         | specify the default ip                |
| onChange     | Function(value:string)  |         | called when input value change        |
| isError      | Function                |         | custom function to check value        |
| prefix       | String                  |         | a prefix  describtion                 |
| mode         | String                  |         | support value: "segment"              |

### Example

run `npm start` and open `http://localhost:8080`

online example: http://lizheming.github.io/iput

### License

IPut is released under the MIT license.
