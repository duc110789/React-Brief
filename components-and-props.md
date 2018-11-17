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

### Rendering Component

1. DOM tags
```
const element = <div />;
```

2. Also represent user-defined component
```
const element = <Welcom name='Duc' />
```

##### Example:
```
function Welcome(props) {
  return <h1>Name, {props.name}</h1>
}
const element = <Welcom name='Duc' />
ReactDom.render(
  element,
  document.getElementById('root')
);
```
