# Interactive Timetabling App

A modern, interactive timetabling application with support for multiple colleges and improved drag-and-drop functionality.

## Features

✨ **Multi-College Support**
- Add and manage multiple colleges
- Switch between colleges instantly
- Each college has its own independent timetable

🎯 **Improved Drag-and-Drop**
- Cell-level drop indicators (no more row/column highlighting)
- Subtle dashed border shows exact drop location
- Ghost clone follows your cursor
- Minimal visual noise during dragging

📱 **Responsive Design**
- Works on desktop and tablet
- Clean, modern interface
- Smooth animations and transitions

## Getting Started

1. Open `index.html` in your web browser
2. Select a college from the dropdown or add a new one
3. Drag sessions to rearrange them in the timetable

## Adding a New College

1. Enter the college name in the input field
2. Click "+ Add College"
3. The new college will appear in the dropdown
4. Select it to view its timetable

## Customizing the Timetable

Edit the `initializeSampleData()` function in `index.html` to:
- Add more colleges
- Modify session names
- Add more time slots
- Change the days of the week

## Technical Details

- **Pure JavaScript** - No dependencies required
- **Modern CSS** - Flexbox and CSS Grid
- **Drag-and-Drop** - Custom implementation with precise cell detection
- **Responsive** - Mobile-friendly design

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

MIT License - Feel free to use and modify as needed
