# css-squares

Functional CSS for squares

## Filesize

| File | Size |
|------|------|
| `dist/squares.css` | 1899 bytes |
| `dist/squares.min.css` | 1201 bytes (237 Gzipped) |

## Install

```sh
npm install css-squares
```

## Usage

### Import

```css
@import "css-squares";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-squares/dist/squares.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-squares/dist/squares.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.sq1` | `width: 1rem;   height: 1rem;` |
| `.sq2` | `width: 2rem;   height: 2rem;` |
| `.sq3` | `width: 4rem;   height: 4rem;` |
| `.sq4` | `width: 8rem;   height: 8rem;` |
| `.sq5` | `width: 16rem;   height: 16rem;` |
| `.sq6` | `width: 32rem;   height: 32rem;` |
| `.sq7` | `width: 48rem;   height: 48rem;` |
| `.sq8` | `width: 64rem;   height: 64rem;` |
| `.sq9` | `width: 96rem;   height: 96rem;` |
| `.sq1-s` | `width: 1rem;     height: 1rem;` |
| `.sq2-s` | `width: 2rem;     height: 2rem;` |
| `.sq3-s` | `width: 4rem;     height: 4rem;` |
| `.sq4-s` | `width: 8rem;     height: 8rem;` |
| `.sq5-s` | `width: 16rem;     height: 16rem;` |
| `.sq6-s` | `width: 32rem;     height: 32rem;` |
| `.sq7-s` | `width: 48rem;     height: 48rem;` |
| `.sq8-s` | `width: 64rem;     height: 64rem;` |
| `.sq9-s` | `width: 96rem;     height: 96rem;` |
| `.sq1-m` | `width: 1rem;     height: 1rem;` |
| `.sq2-m` | `width: 2rem;     height: 2rem;` |
| `.sq3-m` | `width: 4rem;     height: 4rem;` |
| `.sq4-m` | `width: 8rem;     height: 8rem;` |
| `.sq5-m` | `width: 16rem;     height: 16rem;` |
| `.sq6-m` | `width: 32rem;     height: 32rem;` |
| `.sq7-m` | `width: 48rem;     height: 48rem;` |
| `.sq8-m` | `width: 64rem;     height: 64rem;` |
| `.sq9-m` | `width: 96rem;     height: 96rem;` |
| `.sq1-l` | `width: 1rem;     height: 1rem;` |
| `.sq2-l` | `width: 2rem;     height: 2rem;` |
| `.sq3-l` | `width: 4rem;     height: 4rem;` |
| `.sq4-l` | `width: 8rem;     height: 8rem;` |
| `.sq5-l` | `width: 16rem;     height: 16rem;` |
| `.sq6-l` | `width: 32rem;     height: 32rem;` |
| `.sq7-l` | `width: 48rem;     height: 48rem;` |
| `.sq8-l` | `width: 64rem;     height: 64rem;` |
| `.sq9-l` | `width: 96rem;     height: 96rem;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.sq1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/squares.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/squares.css` — formatted
- `dist/squares.min.css` — minified

## License

MIT
