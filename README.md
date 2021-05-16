## AI-Powered Voice Assistant Flutter Radio App
This is a radio app where you can ask Alan AI to play some music.

## Features

- Play/Pause Music By User Intreaction
- Alan Voice Assisatan
- Alan Play Music On User Voice Command

## Implatations

```javascript
setupAlan() {
    AlanVoice.addButton("<"Enter your Key">",
        buttonAlign: AlanVoice.BUTTON_ALIGN_RIGHT);
    AlanVoice.callbacks.add((command) => _handleCommand(command.data));
  }
```

## ScreenShot
![image](https://user-images.githubusercontent.com/56160262/118402921-a5996380-b689-11eb-8b92-4a59ce401946.png)

![image](https://user-images.githubusercontent.com/56160262/118402930-b518ac80-b689-11eb-91f0-392a0a8fd2dc.png)

## Documentation
Want to create a voice assistant for your app? To get started with Alan Studio Read to this:-

[Alan Docs](https://alan.app/docs/usage/getting-started)

  
