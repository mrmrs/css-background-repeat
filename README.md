# css-background-repeat

Functional CSS for background-repeat

## Filesize

| File | Size |
|------|------|
| `dist/background-repeat.css` | 1277 bytes |
| `dist/background-repeat.min.css` | 939 bytes (205 Gzipped) |

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
| `.bg-norep` | `background-repeat: no-repeat;` |
| `.bg-x` | `background-repeat: repeat-x;` |
| `.bg-y` | `background-repeat: repeat-y;` |
| `.bg-rep` | `background-repeat: repeat;` |
| `.bg-spc` | `background-repeat: space;` |
| `.bg-rnd` | `background-repeat: round;` |
| `.bg-norep-s` | `background-repeat: no-repeat;` |
| `.bg-x-s` | `background-repeat: repeat-x;` |
| `.bg-y-s` | `background-repeat: repeat-y;` |
| `.bg-rep-s` | `background-repeat: repeat;` |
| `.bg-spc-s` | `background-repeat: space;` |
| `.bg-rnd-s` | `background-repeat: round;` |
| `.bg-norep-m` | `background-repeat: no-repeat;` |
| `.bg-x-m` | `background-repeat: repeat-x;` |
| `.bg-y-m` | `background-repeat: repeat-y;` |
| `.bg-rep-m` | `background-repeat: repeat;` |
| `.bg-spc-m` | `background-repeat: space;` |
| `.bg-rnd-m` | `background-repeat: round;` |
| `.bg-norep-l` | `background-repeat: no-repeat;` |
| `.bg-x-l` | `background-repeat: repeat-x;` |
| `.bg-y-l` | `background-repeat: repeat-y;` |
| `.bg-rep-l` | `background-repeat: repeat;` |
| `.bg-spc-l` | `background-repeat: space;` |
| `.bg-rnd-l` | `background-repeat: round;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.bg-norep-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/background-repeat.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/background-repeat.css` — formatted
- `dist/background-repeat.min.css` — minified

## License

MIT
