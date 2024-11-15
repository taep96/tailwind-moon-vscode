# Tailwind Color Themes

A set of matching dark and light themes based on Tailwind CSS's default color scheme. These themes were based on Praveen Puglia's excellent “Tailwind Breeze” theme.

## Changelog
## 3.0.2
- Fix italics in Tailwind Ice that aren't present in Tailwind Moon because I forgot to remove from my personal tweaks

## 3.0.1
- Fix terminal selection colors and double squiggly lines in Tailwind Ice

## 3.0.0
- Added Tailwind Ice theme, a light theme based on the Tailwind Moon 2.5 syntax highlighting
- Changed name of extension

## 2.5.3
- Fixed terminal selection colors
- Fixed double squiggly lines

## 2.5.2
- Fixed dumb oversight in 2.5.1

## 2.5.1
- Changed HTML tags to blue to avoid collision with control keywords
- Use 300 cyan for better visibility

### 2.5
- Added a new cyan color for HTML attributes and function calls
- Changed HTML attribute color to purple, in order to make React components distinct in JSX

### 2.4
- Added _Tailwind Moon Gray_ theme using Tailwind's `colors.gray` palette instead of `colors.coolGray`
- Added _Tailwind Moon Blue_ theme using Tailwind's `colors.blueGray` palette instead of `colors.coolGray`
- Fixed selected list item background color being identical to the widget background, making focused items in the Command Palette hard to distinguish

### 2.3.2
- Required due to README.md edit

### 2.3.0
- Changed terminal background color to fit text editor.
- Changed Git colors to be less intrusive.
- Fixed light mode file icons being used instead of dark mode file icons; this was apparently because the theme was still declared as a light theme. It's now declared as a dark theme.
- Darkened sidebar slightly.
- Tweaked highlight colors in sidebar.
- Fixed title bar text color being too dark and hard to read.
- Fixed widget shadow (on e.g. find, command palette) being white instead of dark.

## Installation
VS Code Marketplace: https://marketplace.visualstudio.com/items?itemName=shadowblood.tailwind-moon

## Screenshots
![Screenshot of Tailwind Moon theme with sample code](./screenshots/scr-1.png)
