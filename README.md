# youtube-lecture-helper

유튜브에 있는 강의를 들을때 도와주는 기능들입니다.

capture.py는 강의에서 ppt를 추출해줍니다.

video_download.py는 동영상을, audio_download.py는 오디오를 다운로드 할 수 있습니다.

capture_from_local.py는 로컬파일이 있을때 ppt를 추출해줍니다.

ppt 캡쳐시 저장된 사진의 이름은 강의에서 해당 장면이 나타난 시간입니다.


## 사용한 라이브러리

```
numpy==1.19.2
opencv-python==4.4.0.44
pafy==0.5.5
youtube-dl==2020.9.20
```



## 사용법

용도에 맞는 모듈을 실행시킨후 유튜브url을 입력하면 됩니다.
capture_from_local.py는 실행후 상대경로를 입력하면 됩니다.


