# My Color Palette

My Color Palette is the color system I use across my personal projects for visual identity and consistency. It defines primary, accent, and neutral tones, shown as an interactive click-to-copy wheel and legend with each color name, hex code, and role.

**[Open the interactive wheel →](https://LawrenceOtieno.github.io/My-Color-Palette/)**

<br/>

![My Color Palette](palette-wheel.svg)

<br/>

## The Palette

### Primary

| Swatch | Name | Hex |
|:---:|---|---|
| ![#06283D](https://placehold.co/20x20/06283D/06283D.png) | Navy | `#06283D` |
| ![#0a3d5c](https://placehold.co/20x20/0a3d5c/0a3d5c.png) | Navy Mid | `#0a3d5c` |
| ![#1a5276](https://placehold.co/20x20/1a5276/1a5276.png) | Navy Light | `#1a5276` |

### Accent

| Swatch | Name | Hex |
|:---:|---|---|
| ![#F5820D](https://placehold.co/20x20/F5820D/F5820D.png) | Orange | `#F5820D` |
| ![#B8610A](https://placehold.co/20x20/B8610A/B8610A.png) | Orange Dark | `#B8610A` |
| ![#0D9488](https://placehold.co/20x20/0D9488/0D9488.png) | Teal | `#0D9488` |

### Support

| Swatch | Name | Hex |
|:---:|---|---|
| ![#2196F3](https://placehold.co/20x20/2196F3/2196F3.png) | Blue | `#2196F3` |
| ![#1565C0](https://placehold.co/20x20/1565C0/1565C0.png) | Blue Dark | `#1565C0` |
| ![#64B5F6](https://placehold.co/20x20/64B5F6/64B5F6.png) | Blue Light | `#64B5F6` |

### Neutral & Text

| Swatch | Name | Hex |
|:---:|---|---|
| ![#ffffff](https://placehold.co/20x20/ffffff/e2e8ee.png) | White | `#ffffff` |
| ![#f4f8fb](https://placehold.co/20x20/f4f8fb/e2e8ee.png) | Off-White | `#f4f8fb` |
| ![#3d6680](https://placehold.co/20x20/3d6680/3d6680.png) | Text Mid | `#3d6680` |
| ![#d0e8f2](https://placehold.co/20x20/d0e8f2/d0e8f2.png) | Text Light | `#d0e8f2` |

<br/>

## Usage

Drop these into any project's `:root`:

```css
:root {
  --navy:        #06283D;
  --navy-mid:    #0a3d5c;
  --navy-light:  #1a5276;

  --orange:      #F5820D;
  --orange-dark: #B8610A;
  --teal:        #0D9488;

  --blue:        #2196F3;
  --blue-dark:   #1565C0;
  --blue-light:  #64B5F6;

  --white:       #ffffff;
  --off-white:   #f4f8fb;
  --text-mid:    #3d6680;
  --text-light:  #d0e8f2;
}
```

<br/>

## What's in this repo

| File | Purpose |
|---|---|
| `index.html` | The interactive color wheel and legend — click any color to copy its hex code. Live at the Pages link above. |
| `palette-wheel.svg` | A static snapshot of the wheel, embedded above for anyone browsing the repo. |
| `README.md` | This file. |
