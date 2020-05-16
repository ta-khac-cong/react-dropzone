# ✨Magic Dropzone [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Drag-and-drop%20files%20or%20urls!%20Built%20for%20React:&url=https://github.com/ta-khac-cong/react-dropzone&hashtags=react,component,dropzone,developers)

![screenshot](./demo.png)

## Installation

```bash
yarn add react-magic-dropzone
```
or:
```bash
npm install --save react-magic-dropzone
```

## Usage

Import `MagicDropzone` in your React component:

```javascript static
import MagicDropzone from 'react-magic-dropzone'
```

```jsx
onDrop = (accepted, rejected, links) => {
  // Have fun
}
```

```jsx
<MagicDropzone
  accept="image/jpeg, image/png, .jpg, .jpeg, .png"
  onDrop={this.onDrop}
>
  Drop some files on me!
</MagicDropzone>
```