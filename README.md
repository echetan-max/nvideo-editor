# Zoomscape Video Editor

A powerful web-based video editor built with React, TypeScript, and FFmpeg.wasm. Edit videos directly in your browser with zoom effects, trimming, and real-time preview.

## Features

- 🎥 **Video Import** - Support for MP4, AVI, MOV, and other video formats
- 🔍 **Zoom Effects** - Add dynamic zoom effects with customizable timing and positioning
- ✂️ **Video Trimming** - Trim videos to specific time segments
- 🎬 **Real-time Preview** - See your edits in real-time as you make them
- 📤 **Export** - Download edited videos with all effects applied
- 🎛️ **Timeline** - Visual timeline with zoom effects and trim markers
- 🔊 **Audio Controls** - Volume control and mute functionality

## Prerequisites

- **Node.js** (version 18 or higher)
- **npm** or **yarn** package manager

## Installation

1. **Clone the repository:**
   ```bash
   git clone mygit link
   cd zoomscape-video-editor
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to `http://localhost:5173` (or the URL shown in your terminal)

## Usage

### Basic Workflow

1. **Import Video** - Click "Import Video" and select your video file
2. **Add Zoom Effects** - Use the zoom controls to add zoom effects at specific times
3. **Trim Video** - Use the timeline to set trim points
4. **Preview** - Play the video to see your edits in real-time
5. **Export** - Click "Export" to download your edited video

### Zoom Effects

- **Add Zoom** - Click "Add Zoom" to create a new zoom effect at the current time
- **Adjust Timing** - Set start and end times for each zoom effect
- **Customize Zoom** - Adjust zoom level (100-300%) and position (X/Y coordinates)
- **Preview** - See zoom effects applied in real-time during playback

### Video Trimming

- **Set Trim Points** - Use the timeline to mark start and end points
- **Preview Trim** - The video will only play within the trimmed segment
- **Export Trimmed** - Export only the trimmed portion of the video

## Technical Details

### Built With
- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **FFmpeg.wasm** - Video processing in the browser
- **Tailwind CSS** - Styling
- **shadcn/ui** - UI components
- **Lucide React** - Icons

### Browser Compatibility
- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

**Note:** FFmpeg.wasm requires a modern browser with WebAssembly support.

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Project Structure

```
src/
├── components/          # React components
│   ├── VideoEditor.tsx  # Main video editor component
│   ├── Timeline.tsx     # Timeline component
│   ├── ZoomControls.tsx # Zoom effect controls
│   └── ui/             # shadcn/ui components
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
└── pages/              # Page components
```

## Troubleshooting

### Common Issues

1. **FFmpeg not loading** - Ensure you have a stable internet connection for initial FFmpeg core download
2. **Video not playing** - Check that your video format is supported by the browser
3. **Export fails** - Try with a smaller video file or check browser console for errors

### Performance Tips

- Use smaller video files for faster processing
- Close other browser tabs to free up memory
- Use Chrome/Chromium for best performance

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues or have questions, please open an issue on GitHub. 
