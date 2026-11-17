# ScriptFollower 3

ScriptFollower 3 is a powerful script following application that combines text processing with audio playback capabilities. It allows users to follow scripts with synchronized sound cues, supporting multiple document formats and advanced audio features.

## Features

- **Multi-format Document Support**: Process ODT documents and other formats
- **Audio Playback Integration**: Synchronized sound cues with precise timing
- **Script Line Management**: Advanced script line handling with annotations
- **Web Audio API Integration**: Modern audio processing capabilities
- **Responsive UI**: Clean, modern interface for script following

## Architecture

The application follows a modular architecture with:

- **Document Processing**: Handles parsing and processing of various document formats
- **Audio Playback System**: Integrated sound cue management and playback
- **UI Components**: Vue 3 components for the user interface
- **State Management**: Centralized state handling using Vue's reactivity system

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Install dependencies:
```bash
cd ScriptFollower3/ScriptFollower3
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Project Structure

```
ScriptFollower3/
├── src/                 # Source code
│   ├── components/      # Vue components
│   ├── modules/         # Core modules (soundManager, documentProcessor, etc.)
│   ├── views/           # Application views
│   └── css/             # CSS styles
├── public/              # Static assets
├── context/             # Architecture and documentation
├── TestData/            # Test data files
└── package.json         # Project dependencies and scripts
```

## Audio Playback Optimization Roadmap

For audio playback improvements, see [AudioPlaybackOptimizationRoadmap.md](context/AudioPlaybackOptimizationRoadmap.md)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Vue.js team for the excellent framework
- Web Audio API contributors
- Ensure keyboard navigation works for all interactive elements.
- Use semantic HTML and ARIA attributes where appropriate.

## Testing
- Unit tests should be placed in `/src/__tests__/`.
- Use Jest or Vitest for testing.

## Comments
- Use line comments (`// ...`) for inline explanations.
- Use block comments (`/** ... */`) for function documentation.

## File Naming
- Use camelCase for JS/TS files and PascalCase for Vue components.

## Example Imports
```js
import { reactive, ref, watch } from 'vue'
import { DocumentProcessor } from './modules/documentProcessor'
import { useSpeechRecognition } from './modules/speechRecognition'
```

## Example State
```js
const state = reactive({
  message: '',
  error: '',
  transcript: '',
  listening: false,
  // ...other fields
})
```

---

**Always follow these rules when generating or modifying code for this project.**