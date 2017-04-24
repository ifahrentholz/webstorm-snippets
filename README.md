# Webstorm React Snippets (Live Templates)

### Install snippets

1. Download the `live_template.jar` file
2. Open Webstorm (Or any other IDEA IDE)
3. Goto `File > Import Settings` and select the live_template.jar file

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


### Polymer (v1)

| Abbreviation | Description |
|---|---|
| arrsel→ | array-selector id="$id$" { ... } |
| ce→ | Object.create(HTMLElement.prototype) |
| domb→ | template is="dom-bind" { ... } |
| domi→ | template is="dom-if" if={{$isEnabled$}} { ... } |
| domr→ | template is="dom-repeat" items={{$array$}} { ... } |
| fba→ | firebase-auth id="$firebaseAuth$" { ... } |
| hi→ | link rel="import" href="..." |
| hii→ | link rel="import" href="iron-element/iron-element.html |
| hip→ | link rel="import" href="../paper-{...}" |
| iron-a11y-keys→ | iron-a11y-keys keys="{ ... }" |
| iron-ajax→ |  iron-ajax url="{ ... } |
| iron-autogrow-textarea→ | iron-autogrow-textarea { ... } |
| iron-collapse→ | iron-collapse id="$collapse$" |
| iron-doc-viewer→ | iron-doc-viewer descriptor="{...} |
| iron-form→ | form is="{ ... }" id="{ ... }" method="{ ... }" |
| iron-icon→ | iron-icon icon="{ ... }" |
| iron-iconset→ | iron-iconset name="{...}" src="{...}" ... |
| iron-iconset-svg→ | iron-iconset-svg name="{...}" size="{...}" |
| iron-image→ | iron-image src="$0$" $preload$ sizing="$cover$" |
| iron-input→ | input is="iron-input" bind-value="{{$myValue$}}" |
| iron-localstorage→ | iron-localstorage name="$my_app_storage$" value="{{$value$}}" |
| iron-media-query→ | iron-media-query query="$min_width_640$" query-matches="{{$largeScreen$}}" |
| iron-meta→ | iron-meta key="$info$" |
| iron-pages→ | iron-pages selected="$0$" |
| iron-selector→ | iron-selector selected="$0$" |
| paper-autogrow-textarea→ | paper-autogrow-textarea id="$a1$" |
| paper-button→ | paper-button $raised$ |
| paper-card→ | paper-card heading="$card_title$" $image$ elevation="$0$" animated-shadow="$false$" |
| paper-checkbox→ | paper-checkbox $checked$ |
| paper-dialog→ | paper-dialog |
| paper-drawer-panel→ | paper-drawer-panel |
| paper-fab→ | paper-fab icon="$add$" |
| paper-header-panel→ | paper-header-panel class="flex" |
| paper-icon-button→ | paper-icon-button icon="$END$" |
| paper-input→ | paper-input label="$0$" |
| paper-item→ | paper-item |
| paper-material→ | paper-material elevation="$1$" |
| paper-menu→ | paper-menu $multi$ |
| paper-progress→ | paper-progress value="$10$" |
| paper-radio-button→ | paper-radio-button |
| paper-radio-group→ | paper-radio-group selected="$small$" |
| paper-ripple→ | paper-ripple |
| paper-scroll-header-panel→ | paper-scroll-header-panel $condenses$ class="flex" |
| paper-slider→ | paper-slider min="$10$" max="$200$" value="$110$" |
| paper-spinner→ | paper-spinner $active$ |
| paper-tab→ | paper-tab |
| paper-tabs→ | paper-tabs selected="$0$" |
| paper-toast→ | paper-toast text="$Your_draft_has_been_discarded$" |
| paper-toggle-button→ | paper-toggle-button $checked$ |
| paper-toolbar→ | paper-toolbar class="$tall$" |
| paper-tooltip→ | paper-tooltip for="$0$" position="$bottom$" offset="$14$" |
| pe→ | Polymer Element |
| pefs→ | Polymer Element full strict |
| pes→ | Polymer element, external styles |
| ph→ | Polymer html boilerplate |
| template→ | template$0$ |
| webcomponents→ | script include |



