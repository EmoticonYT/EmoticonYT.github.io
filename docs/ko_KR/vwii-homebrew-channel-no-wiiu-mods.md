# 홈브류 채널 설치

이 페이지에서는 Wii U 쪽을 개조하지 않고 vWii에 홈브류 채널을 설치하는 과정을 안내합니다.

## 지침

### 섹션 I - 아로마로 부팅하기

1. [이전에 설명한 대로](wiiu-nand-dumper) 웹 브라우저 익스플로잇을 실행하지만, 이번에는 X 버튼을 눌러 환경 로더 메뉴를 열어야 합니다.
2. 해당 위치에 가면, 페이로드 로더 내부에서 아로마 환경을 선택하여 부팅합니다.

### 섹션 II - 홈브류 채널 설치

1. Wii U 메뉴에서 vWii Compat 설치 프로그램을 실행합니다.
2. `A` 버튼을 눌러 홈브류 채널을 설치하고 `설치 성공`이 나올 때까지 기다립니다. 그런 다음 홈 버튼을 눌러 Wii U 메뉴로 돌아갑니다.
3. vWii (Wii 메뉴 아이콘)를 실행합니다.
 - 설치가 성공적으로 완료되면, Wii 메뉴에 홈브류 채널이 표시됩니다.

원하시면 SD 카드에서 `wiiu` 폴더를 삭제해도 됩니다.

## 필수 읽기

이제 홈브류 채널을 사용하여 Wii 홈브류 앱을 실행할 수 있습니다.

참고: SD 카드나 USB 드라이브에 홈브류 응용 프로그램을 설치할 때 폴더 구조는 다음과 같아야 합니다:

```
💾 SD 카드
 ┗ 📁 apps
   ┣ 📁 <AppName1>
   ┃ ┣ 📄 boot.dol
   ┃ ┣ 📄 meta.xml
   ┃ ┗ 📄 icon.png
   ┗ 📁 <AppName2>
     ┣ 📄 boot.dol
     ┣ 📄 meta.xml
     ┗ 📄 icon.png
```

`AppName1`과 `AppName2`는 플레이스홀더 이름입니다. `apps` 폴더 자체 내에 여러 개의 `apps` 폴더를 중첩하지 마세요.
`wiiu` 폴더 내의 `apps` 폴더와 SD 카드 루트의 `apps` 폴더를 혼동하지 마세요.

::: tip

[Priiloader 설치 계속하기](priiloader)

:::
