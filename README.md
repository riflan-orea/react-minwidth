# MinWidth React Component

A simple React component to set a minimum width for its children.

## Installation

    $ npm install react-minwidth

## Usage

```tsx
import { MinWidth } from "react-minwidth";

function App() {
  return (
    <MinWidth size={200}>
      <div>This content will have a minimum width of 200px</div>
    </MinWidth>
  );
}
```

## Props

- `width` (number): The minimum width in pixels
- `children` (ReactNode): The content to be wrapped

## License

MIT
