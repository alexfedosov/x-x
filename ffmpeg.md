<img width="620" alt="Screenshot 2023-01-05 at 11 36 19" src="https://user-images.githubusercontent.com/919187/210760280-00b0a4ab-fb2a-4354-a57e-3f7b37a4e12d.png">

```bash
brew install ffmpeg
```

---

### How to

Convert `.mov` to `.mp4`
```bash
ffmpeg -i source.mov -vcodec h264 -acodec aac target.mp4
```


Convert `.mov` to `.webm`
```bash
ffmpeg -i source.mov -c:v libvpx -crf 10 -b:v 1M -c:a libvorbis target.webm
```

