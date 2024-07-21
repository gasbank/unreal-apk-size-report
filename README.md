# unreal-apk-size-report

<img width="407" alt="image" src="https://github.com/user-attachments/assets/f089447f-98ed-4a82-92c2-cd3847d08815">

잉여톤 34회 참가 시 개발했던 프로그램입니다.

아래 링크에서 34회 공고를 확인할 수 있습니다.

https://github.com/yingyeothon/yingyeothon.github.io/issues/46

공고 아래에 제가 개발 전에 당초 계획했던 목표를 아래에 붙여넣었습니다.

### 제목: `APK` 파일과 나의 진솔한 대화

최근 한달 반 동안 언리얼을 쓰고 있는데, 유니티에 비해 부족한 몇 가지가 있었습니다. 그 중 하나는 최종 빌드 결과물이 나왔을 때 이 빌드 내 리소스별 용량 비율을 쉽게 보는 기능이 없다는 점입니다.

예를 들어 안드로이드 앱 설치 파일 APK가 최종 빌드 결과물로 나왔는데, 이 파일 내에 텍스쳐는 몇 %를 차지하고, 폰트는 몇 %를 차지하고, 코드는 몇 %를 차지하고 등을 알려주지 않는다는 것입니다.

그래서... 최종 결과물인 APK의 압축을 풀고, 거기에서 나오는 PAK 파일을 UnrealPak으로 또 압축을 풀고 하는 식으로 용량 분포를 수동으로 봐야 하는데, 매우 귀찮은 일입니다.

APK 파일이 나오면, 이 파일의 리소스별 용량 리포트를 자동으로 출력하는 개발을 해 보려고 합니다.

이로서 APK의 속마음을 알아낼 수 있기를...