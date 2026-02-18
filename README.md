# Heatmap

A simple heatmap github-like template showing how to use **@uiw/react-heat-map** to render a GitHub-style contribution heatmap in React with custom colors and styling.

## Preview

![Heatmap preview](./heatmap.png)

## Features

* 1-year heatmap example
* Random sample data generation
* Custom dark theme colors
* Rounded cells and clean layout
* Easy to adapt for real data

## Installation

```bash
npm install @uiw/react-heat-map
```

## Usage

Import and use the component:

```tsx
import HeatMapTemplate from "./HeatMapTemplate";

function App() {
  return <HeatMapTemplate />;
}

export default App;
```

## Notes

* The current example generates random values just for demonstration.
* Replace the generated `value` array with real data from your application.

## License

MIT
