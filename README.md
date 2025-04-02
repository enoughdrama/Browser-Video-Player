<img width="1022" alt="image" src="https://github.com/user-attachments/assets/a9546bb9-7521-4681-b059-5076f84cb052" />

## Key Features

- Minimalist interface with focused interactions
- Frame-accurate playback controls
- Context-aware thumbnails and previews
- Seamless volume adjustments
- Intelligent chapter navigation
- Keyboard command support (press `?`)
- Responsive design for all screens

## Implementation

### Basic Setup

```html
<!-- Include player in your project -->
```

### Customize

```html
<video id="video" poster="poster.jpg" playsinline>
  <source src="video.mp4" type="video/mp4">
</video>
```

### Add Chapters

```javascript
const chapters = [
  { time: 0, title: "Introduction" },
  { time: 120, title: "Main Content" }
];
```

## Compatibility

Designed for modern browsers supporting HTML5 video.
