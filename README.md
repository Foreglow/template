# Foreglow Theme Template

Use this repository as a template to create a new Foreglow theme for your favorite application.

## Variants

- **Foreglow** — Dark theme (dawn — the glow *before* first light)
- **Afterglow** — Light theme (dusk — the glow *after* sunset)

## Getting Started

1. Click "Use this template" on GitHub to create a new repository under your account
2. Clone your new repository
3. Install dependencies (if any)
4. Create your theme using the Foreglow or Afterglow color palette
5. Submit an issue at [Foreglow/foreglow-theme](https://github.com/Foreglow/foreglow-theme) with your repo link

## Color Palettes

### Foreglow (Dark)

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Background** | `#161221` | 22, 18, 33 | Main background |
| **Bg Alt** | `#1D182A` | 29, 24, 42 | Sidebar, panels |
| **Current Line** | `#281F3D` | 40, 31, 61 | Line highlight |
| **Selection** | `#3D2556` | 61, 37, 86 | Text selection |
| **Border/Gutter** | `#322C44` | 50, 44, 68 | Borders, gutters |
| **Foreground** | `#E8E3F2` | 232, 227, 242 | Default text |
| **Foreground Dim** | `#A49BBF` | 164, 155, 191 | Secondary text |
| **Comment** | `#736699` | 115, 102, 153 | Comments |
| **Keyword** | `#CB81E4` | 203, 129, 228 | Keywords |
| **String** | `#ED9F82` | 237, 159, 130 | Strings |
| **Function** | `#EC93BF` | 236, 147, 191 | Functions |
| **Number** | `#EFBF6C` | 239, 191, 108 | Numbers |
| **Class/Type** | `#75C6D7` | 117, 198, 215 | Classes, types |
| **Variable** | `#C7BCE6` | 199, 188, 230 | Variables |
| **Operator** | `#A085AD` | 160, 133, 173 | Operators |
| **Error** | `#E46772` | 228, 103, 114 | Errors |
| **Warning** | `#F2A65A` | 242, 166, 90 | Warnings |
| **Success** | `#6BC7A8` | 107, 199, 168 | Success |
| **Cursor/Accent** | `#F471C8` | 244, 113, 200 | Cursor, accent |

### Afterglow (Light)

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Background** | `#F4EEE1` | 244, 238, 225 | Main background |
| **Bg Alt** | `#ECE5D5` | 236, 229, 213 | Sidebar, panels |
| **Current Line** | `#E6D6C1` | 230, 214, 193 | Line highlight |
| **Selection** | `#DFC2AA` | 223, 194, 170 | Text selection |
| **Border/Gutter** | `#CDAEA2` | 205, 174, 162 | Borders, gutters |
| **Foreground** | `#24163B` | 36, 22, 59 | Default text |
| **Foreground Dim** | `#574979` | 87, 73, 121 | Secondary text |
| **Comment** | `#7A6F9B` | 122, 111, 155 | Comments |
| **Keyword** | `#8930A6` | 137, 48, 166 | Keywords |
| **String** | `#B64820` | 182, 72, 32 | Strings |
| **Function** | `#AE296B` | 174, 41, 107 | Functions |
| **Number** | `#955F0F` | 149, 95, 15 | Numbers |
| **Class/Type** | `#1D7187` | 29, 113, 135 | Classes, types |
| **Variable** | `#4D3781` | 77, 55, 129 | Variables |
| **Operator** | `#7F5893` | 127, 88, 147 | Operators |
| **Error** | `#B12531` | 177, 37, 49 | Errors |
| **Warning** | `#A25410` | 162, 84, 16 | Warnings |
| **Success** | `#22775B` | 34, 119, 91 | Success |
| **Cursor/Accent** | `#C3228E` | 195, 34, 142 | Cursor, accent |

## ANSI Colors

### Foreglow (Dark)

| Slot | Hex | Usage |
|------|-----|-------|
| ANSI Black | `#161221` | Background |
| ANSI Red | `#E46772` | Error |
| ANSI Green | `#6BC7A8` | Success |
| ANSI Yellow | `#F2A65A` | Warning |
| ANSI Blue | `#75C6D7` | Type |
| ANSI Magenta | `#CB81E4` | Keyword |
| ANSI Cyan | `#EC93BF` | Function |
| ANSI White | `#A49BBF` | Dim foreground |
| ANSI Bright Black | `#322C44` | Border |
| ANSI Bright Red | `#E46772` | Error |
| ANSI Bright Green | `#6BC7A8` | Success |
| ANSI Bright Yellow | `#F2A65A` | Warning |
| ANSI Bright Blue | `#75C6D7` | Type |
| ANSI Bright Magenta | `#CB81E4` | Keyword |
| ANSI Bright Cyan | `#EC93BF` | Function |
| ANSI Bright White | `#E8E3F2` | Foreground |

### Afterglow (Light)

| Slot | Hex | Usage |
|------|-----|-------|
| ANSI Black | `#24163B` | Foreground |
| ANSI Red | `#B12531` | Error |
| ANSI Green | `#22775B` | Success |
| ANSI Yellow | `#A25410` | Warning |
| ANSI Blue | `#1D7187` | Type |
| ANSI Magenta | `#8930A6` | Keyword |
| ANSI Cyan | `#AE296B` | Function |
| ANSI White | `#574979` | Dim foreground |
| ANSI Bright Black | `#CDAEA2` | Border |
| ANSI Bright Red | `#B12531` | Error |
| ANSI Bright Green | `#22775B` | Success |
| ANSI Bright Yellow | `#A25410` | Warning |
| ANSI Bright Blue | `#1D7187` | Type |
| ANSI Bright Magenta | `#8930A6` | Keyword |
| ANSI Bright Cyan | `#AE296B` | Function |
| ANSI Bright White | `#24163B` | Foreground |

## File Structure

```
.
├── README.md
├── LICENSE
└── src/
    ├── foreglow.yml      # dark theme source
    └── afterglow.yml     # light theme source
```

## Guidelines

- Follow the color palette exactly as specified above
- Include a `README.md` with installation instructions and a screenshot
- Include a `LICENSE` file (MIT)
- Support both light and dark variants if the application supports it
- Test your theme on at least one other platform if possible
- Keep theme files in the standard location for the application

## Submitting

Once your theme is ready, submit an issue at [Foreglow/foreglow-theme](https://github.com/Foreglow/foreglow-theme) with:
- Link to your repository
- Screenshot of the theme
- List of supported features/versions

If accepted, your repository will be transferred to the Foreglow organization.
