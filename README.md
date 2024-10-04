# Unity-Lamentum

Lamentum 한국어 패치

- 게임 데이터의 저작권은 모두 개발사 혹은 배급사에 있습니다.
  - ~~이 패치는 개발사 혹은 배급사의 요청에 의해 언제든 삭제될 수 있습니다.~~
  - 개발사 허가 받았습니다. (Oct 4, 2024)
- 수정 및 재배포 금지입니다.
- 후반부에 등장하는 동상과 묘비명은 후원자 메시지로 보여서 번역하지 않았습니다.

## 게임

- [스팀 상점 페이지](https://store.steampowered.com/app/1033950/Lamentum/)
- [GOG 상점 페이지](https://www.gog.com/en/game/lamentum)
- Version 1.0.5 | Build 0.7.48

## 사용법

1. [최신 Release](https://github.com/killterm/Unity-Lamentum/releases)를 게임 설치 경로에 다운로드
2. 압축 해제
   - `/Lamentum_Data/resources.assets` 파일 덮어쓰기

## Checksum

아래 명령의 결과값이 `True`여야 함.

### Original

```ps1
(Get-FileHash -Algorithm MD5 resources.assets).Hash -eq "3382A7131C78013BAC87D36F2719C008"
```

### Patch

```ps1
(Get-FileHash -Algorithm MD5 resources.assets).Hash -eq "EFE8916109140FBCE937D1320659CCE4"
```
