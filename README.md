# Mistppuccin
### The color palette for tilley.lol

# Color Palette

## Surface Stack
| Role     | Hex       | Usage               |
| -------- | --------- | ------------------- |
| Base     | `#111111` | Main background     |
| Mantle   | `#181818` | Section backgrounds |
| Crust    | `#0a0a0a` | Elevated surfaces   |
| Surface0 | `#202020` | Cards               |
| Surface1 | `#2a2a2a` | Hover surfaces      |
| Surface2 | `#343434` | Active surfaces     |

---

## Text Hierarchy
| Role     | Hex       |
| -------- | --------- |
| Text     | `#e6e6e6` |
| Subtext1 | `#cfcfcf` |
| Subtext0 | `#b5b5b5` |
| Overlay2 | `#767676` |
| Overlay1 | `#5a5a5a` |
| Overlay0 | `#3f3f3f` |

## Accent System
| Role      | Hex       | Description           |
| --------- | --------- | --------------------- |
| Rosewater | `#dcdcdc` | Soft highlight        |
| Flamingo  | `#c8c8c8` | Active accent         |
| Pink      | `#b4b4b4` | Secondary accent      |
| Mauve     | `#a0a0a0` | Muted mid-tone        |
| Red       | `#8c8c8c` | Bold accent           |
| Maroon    | `#787878` | Primary button color  |
| Peach     | `#646464` | Warm mid              |
| Yellow    | `#505050` | Muted dark            |
| Green     | `#3c3c3c` | Deep surface          |
| Teal      | `#2e2e2e` | Near-black surface    |
| Sky       | `#242424` | Deep background tone  |
| Sapphire  | `#1c1c1c` | Darkest surface       |
| Blue      | `#161616` | Near void             |
| Lavender  | `#101010` | Void adjacent         |

---

# Customization
All colors are controlled via CSS variables inside `:root`:
```css
:root {
    --base:     #111111;
    --mantle:   #181818;
    --crust:    #0a0a0a;
    --surface0: #202020;
    --surface1: #2a2a2a;
    --surface2: #343434;
    --text:     #e6e6e6;
    --subtext1: #cfcfcf;
    --subtext0: #b5b5b5;
}
```

# Inspiration
* Catppuccin color system
* Monochrome grayscale tones
