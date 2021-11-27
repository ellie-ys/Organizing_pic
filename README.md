# Organizing_pic

node.js를 활용한 사진 정리 스크립트 만들기.

```

google photo에 사진 파일 업로드 시, 사용하는 스크립트

1. Pictures 폴더 안에 달별로 폴더 만들어 준다.
2. 사진과 동영상을 분리
3. video폴더에 video file 넣고
4. duplicated 폴더에 수정한 파일이 있을 때만 그 원본사진 IMG_****.jpg 넣어주기
5. captured 폴더에 screenshots.png, IMG_####. aae(사진 편집하면 생김) 넣기

```

## 실행 방법

node <노드 app 이름> <사용하고자하는 폴더 이름>
`node organizing_photo test`

어떻게 처리되었는지 알 수 있는 간단한 로그도 보여준다.

### 실행 후 폴더 구조

파일 이름 : <확장자>

```
└─Pictures
     └─jan :<.jpg>
         ├─captured : <.png, .aae>
         ├─duplicated : <.jpg(수정한 파일이 있을 때만 원본 파일)>
         └─video : <.mov, .mp4>
    └─feb :<.jpg>
    ...
```

refer 
[노드 입문자](https://nodejs.dev/learn)

[노드 공식 사이트](https://nodejs.org/en/docs/)


