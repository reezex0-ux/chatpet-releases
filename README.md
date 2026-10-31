# chatpet

컴퓨터 안에 사는 작은 슬라임과 짧게 이야기하는 오프라인 대화 캐릭터입니다. 대화는 모두 이 PC에서 처리합니다(계정·API 키 없음).

**Powered by Kanana**

## 설치

1. [Releases](https://github.com/reezex0-ux/chatpet-releases/releases)에서 `chatpet-setup-<버전>.exe`(약 24MB)를 받아 실행합니다. 관리자 권한은 필요 없습니다.
2. 처음 켜면 **모델 내려받기** 버튼이 나옵니다. 모델(약 2.5GB)을 [chatpet-models](https://github.com/reezex0-ux/chatpet-models)에서 받아 확인한 뒤 바로 대화를 시작합니다. 받다가 끊기면 다시 누를 때 이어서 받습니다.

서명되지 않은 설치 파일이라 Windows가 "알 수 없는 게시자" 경고를 띄울 수 있습니다(추가 정보 → 실행).

## 쓰는 법

- 아래 칸에 말을 걸면 슬라임이 답합니다. 대화는 `%APPDATA%\chatpet`에 저장되어 다시 켜도 이어집니다.
- 슬라임을 끌면 창이 움직이고, 클릭하면 말랑하게 눌리고, **더블클릭**하면 슬라임만 화면 위에 띄워 둡니다(다시 더블클릭하면 대화창).

## 사양

- Windows 10/11 64비트
- 외장 GPU(VRAM 약 3.5GB 이상, Vulkan)가 있으면 그 GPU로, 없으면 CPU로 실행합니다. CPU에서는 답 하나에 보통 1초 안팎입니다.
- 디스크 약 2.7GB

## 라이선스

- 모델: Kanana 2 3B Instruct를 GGUF로 변환·양자화한 파일. Kanana is licensed in accordance with the Kanana Open License Agreement. Copyright © KAKAO Corp. All Rights Reserved. 설치 시 동의 화면과 설치 폴더의 `licenses\`를 보세요.
- llama.cpp(MIT), LLVM OpenMP(Apache 2.0 with LLVM Exceptions).
