### Define Component: two way define

1. Function component
```
function Welcom(props) {
  return <h1>Hello, {props.name}</h1>
}
```

2. ES6 class
```
class Welcom extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1> // this <=> class 'Welcom'
  }
}
```
