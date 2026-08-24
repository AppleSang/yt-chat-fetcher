<div align="center">
  <img width="280" height="160" alt="YouTube Chat Fetcher logo" src="https://github.com/user-attachments/assets/15444b70-0bea-4452-b90a-ec972d8a8ddc" align="right" />
  <h1>YouTube Chat Fetcher</h1>
  <p>Fast setup · Simple to use · Reliable</p>
</div>

<p align="center">
  <a href="README.vi.md">Đọc bằng tiếng Việt</a>
</p>

## Features

- Automatically loads the chat box for a stream.
- Keeps trying until the chat box becomes available.
- Works with custom CSS, so you can style the chat for your stream.

## Video guide

[![Watch the setup video](https://github.com/user-attachments/assets/15444b70-0bea-4452-b90a-ec972d8a8ddc)](https://www.youtube.com/watch?v=-6NTKx266-Q)

## Setup

1. Open the fetcher URL: [https://applesang.github.io/yt-chat-fetcher/?id=](https://applesang.github.io/yt-chat-fetcher/?id=). You will add your YouTube channel handle after `?id=` in a later step.
2. Open [YouTube](https://www.youtube.com/) and click your profile picture.

   <img src="https://github.com/user-attachments/assets/70c84828-ea46-497e-875f-25c6dfe558aa" alt="YouTube profile menu" width="732" height="167" />

3. Select **View your channel**.

   <img src="https://github.com/user-attachments/assets/be5cdc27-8518-4dc6-8b3a-e77ed46d39c0" alt="View your channel option" width="238" height="604" />

4. Copy your channel handle, including the `@` symbol, from the channel URL. For example, copy `@yourchannel` from `youtube.com/@yourchannel`.

   <img src="https://github.com/user-attachments/assets/08ebe67b-bbe3-4ef2-a988-d0183d9df67c" alt="Channel handle in a YouTube URL" width="331" height="44" />

5. Paste the handle after `?id=` in the fetcher URL. For example: `https://applesang.github.io/yt-chat-fetcher/?id=@yourchannel`.

   <img src="https://github.com/user-attachments/assets/e41a67c8-2d0b-42ee-a924-c176a96d0a6c" alt="Fetcher URL with channel handle" width="427" height="46" />

6. Copy the complete URL and add it to OBS as a **Browser Source**.
7. Optional: add the same URL to OBS as a **Custom Browser Dock** for quick access.

> [!TIP]
> Add custom [CSS](https://chatv2.septapus.com/) in OBS to give the chat a cleaner appearance.

## FAQ

<details>
  <summary>Why does the video guide include <code>@</code>, while the older text guide does not?</summary>

The fetcher accepts your channel handle with or without `@`. You can also use your [YouTube channel ID](https://www.youtube.com/account_advanced).

</details>

## Support

Open an [issue](https://github.com/AppleSang/yt-chat-fetcher/issues) to report a bug or request a feature.
