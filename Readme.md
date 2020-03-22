# use-typewriter

This package provides a simple React Hook to delay the print of a given string by a given time (ms).

## API

`useTypewriter({title: string, speed?: number}): string`

## Usage

```
const App = () => {
	const title = useTypewriter({title: 'Test Title', speed: 60})
	return <h1>{title}</h1>
}
```
