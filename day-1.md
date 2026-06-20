[ffmpeg](https://www.ffmpeg.org)을 사용하여 이미지나 동영상을 다크 모드에서 라이트 모드로 변환하기

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
