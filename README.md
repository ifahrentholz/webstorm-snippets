# Webstorm React Snippets (Live Templates)

### Javascript ES6

These are basic ES6 snippets.
 
##### Documentation of available React snippets:

| Abbreviation | Description |
|---|---|
| imp→ | import ... from '...' |
| gfn→  | function* name (arg) { yield arg; } |
| =>→ | (arg) => { ... } |
| class→ | class name { constructor () { ...} } |

### React ES6

This is a fork of mboperator/sublime-react-es6 snippets.

The main difference to the original Facebook snippets are:

- Converted function declarations to the new ES6 shorthand.
- Static class variables (defaultProps, propTypes) are declared using ES7 property intializers.
- ES6 style exports and imports for component creating snippets.
- Added `rrc` for Redux connected components.

##### Documentation of available React snippets:

| Abbreviation | Description |
|---|---|
| cdm→ | componentDidMount: fn() { ... } |
| cdup→ | componentDidUpdate: fn(pp, ps) { ... } |
| cs→ | import cx from 'classnames'; |
| cwm→ | componentWillMount: fn() { ... } |
| cwr→ | componentWillReceiveProps: fn(np) { ... } |
| cwu→ | componentWillUpdate: fn(np, ns) { ... } |
| cwun→ | componentWillUnmount: fn() { ... } |
| cx→ | cx({ ... }) |
| fdn→ | React.findDOMNode(...) |
| fup→ | forceUpdate(...) |
| gdp→ | static defaultProps = { ... } |
| gis→ | getInitialState: fn() { return {...} } |
| ism→ | isMounted() |
| props→ | this.props. |
| pt→ | propTypes { ... } |
| rcc→ | component skeleton |
| refs→ | this.refs. |
| ren→ | render: fn() { return ... } |
| rrc→ | redux component skeleton |
| scu→ | shouldComponentUpdate: fn(np, ns) { ... } |
| sst→ | this.setState({ ... }) |
| state→ | this.state. |


### Install snippets

1. Download the `live_template.jar` file
2. Open Webstorm (Or any other IDEA IDE)
3. Goto `File > Import Settings` and select the live_template.jar file


