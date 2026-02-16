# css-background-repeat

Functional CSS for background-repeat

## Filesize

| File | Size |
|------|------|
| `dist/background-repeat.css` | 1373 bytes |
| `dist/background-repeat.min.css` | 1035 bytes (209 Gzipped) |

## Install

```sh
npm install css-background-repeat
```

## Usage

### Import

```css
@import "css-background-repeat";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-background-repeat/dist/background-repeat.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-background-repeat/dist/background-repeat.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.bg-norepeat` | `background-repeat: no-repeat;` |
| `.bg-repeat-x` | `background-repeat: repeat-x;` |
| `.bg-repeat-y` | `background-repeat: repeat-y;` |
| `.bg-repeat` | `background-repeat: repeat;` |
| `.bg-space` | `background-repeat: space;` |
| `.bg-round` | `background-repeat: round;` |
| `.bg-norepeat-s` | `background-repeat: no-repeat;` |
| `.bg-repeat-x-s` | `background-repeat: repeat-x;` |
| `.bg-repeat-y-s` | `background-repeat: repeat-y;` |
| `.bg-repeat-s` | `background-repeat: repeat;` |
| `.bg-space-s` | `background-repeat: space;` |
| `.bg-round-s` | `background-repeat: round;` |
| `.bg-norepeat-m` | `background-repeat: no-repeat;` |
| `.bg-repeat-x-m` | `background-repeat: repeat-x;` |
| `.bg-repeat-y-m` | `background-repeat: repeat-y;` |
| `.bg-repeat-m` | `background-repeat: repeat;` |
| `.bg-space-m` | `background-repeat: space;` |
| `.bg-round-m` | `background-repeat: round;` |
| `.bg-norepeat-l` | `background-repeat: no-repeat;` |
| `.bg-repeat-x-l` | `background-repeat: repeat-x;` |
| `.bg-repeat-y-l` | `background-repeat: repeat-y;` |
| `.bg-repeat-l` | `background-repeat: repeat;` |
| `.bg-space-l` | `background-repeat: space;` |
| `.bg-round-l` | `background-repeat: round;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.bg-norepeat-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/background-repeat.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/background-repeat.css` — formatted
- `dist/background-repeat.min.css` — minified

## License

MIT
