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
Install dependencies

In pubspec.yaml add these following Packages!!

```bash
  audioplayer: ^0.8.1
  cupertino_icons: ^1.0.2
  google_fonts: ^2.0.0
  velocity_x: ^3.0.0
  alan_voice: ^2.0.15
```

## ScreenShot
![WhatsApp Image 2021-05-16 at 21 06 14 (1)](https://user-images.githubusercontent.com/56160262/118403224-1b51ff00-b68b-11eb-8754-16d8d2fdfcce.jpeg)
![WhatsApp Image 2021-05-16 at 21 06 14](https://user-images.githubusercontent.com/56160262/118403226-1db45900-b68b-11eb-8255-e7a3beb083e8.jpeg)

## Demo
Ps:- you cant be able to hear the audio but its Playing xD

https://user-images.githubusercontent.com/56160262/118403344-9d422800-b68b-11eb-94d3-d677450ba7ac.mp4



## Documentation
Want to create a voice assistant for your app? To get started with Alan Studio Read to this:-

[Alan Docs](https://alan.app/docs/usage/getting-started)



## Tech Stack

**Client:** Flutter,velocitX

**Voice_Assistance:** Alan Ai
