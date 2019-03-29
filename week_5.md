# Weekly recap 5

## ReactJS

### About ReactJS

//Florian / Jonathan  
ReactJS is a javascript library for building user interfaces. It is maintened by Facebook and a community of individual developpers and companies
It can be used as a base in the development of SPA (Single page Application).

## Creating an App
//Perrine

To create a new app, you have to do:

npx create-react-app my-app  
cd my-app  
npm start  

### SPA

---------------------------------------------------------------------------
//Nathalie / Vanessa

### COMPONENTS:
React allows you to define your components as classes or functions.


## Functional component:

A functional component is just a plain JavaScript function which accepts props as an argument and returns a React element.

# Syntax:
```
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```

## Class component:

A class component requires you to extend from React.Component and create a render function which returns a React element.

# Syntax:
```
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
```
--------------------------------------------------------------------------------
## 

### ...
