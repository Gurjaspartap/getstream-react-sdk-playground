# Video Call Application

A real-time video calling application built with React and Stream Video SDK. This project demonstrates the implementation of video calling features using Stream's powerful SDK.

## Features

- Real-time video calling
- Multiple participant support
- Speaker layout for video display
- Call controls (mute, camera toggle, etc.)
- Modern UI with Stream's default theme

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- A Stream account and API credentials

## Setup

1. Clone the repository:
```bash
git clone <your-repo-url>
cd video-call
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Configure your Stream credentials:
   - Get your API key from [Stream Dashboard](https://dashboard.getstream.io)
   - Update the `apiKey` and `token` in `src/App.tsx`

4. Start the development server:
```bash
npm start
# or
yarn start
```

## Environment Variables

Create a `.env` file in the root directory with the following variables:
```
REACT_APP_STREAM_API_KEY=your_api_key
REACT_APP_STREAM_TOKEN=your_token
```

## Technologies Used

- React
- TypeScript
- Stream Video SDK
- CSS Modules

## Project Structure

```
src/
  ├── App.tsx          # Main application component
  ├── index.tsx        # Application entry point
  └── index.css        # Global styles
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Stream Video SDK](https://getstream.io/video/docs/react/introduction/)
- [React Documentation](https://reactjs.org/)
