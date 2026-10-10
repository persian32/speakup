# Speak Up!

**▶ Live site / 접속:** https://persian32.github.io/speakup/

**English summary**

Speak Up is a free web tool that helps Korean high school students practice English speaking and get feedback from the AI assistant they already use (ChatGPT, Gemini, etc.).

- **How it works:** A student speaks in English. Speech recognition runs inside the browser (Whisper base.en via transformers.js), and the page measures speaking rate, intonation range, and long pauses. One tap opens ChatGPT with a prepared request, or the student copies it into another AI.
- **Privacy:** The voice never leaves the device. Only the transcribed text is sent, and only to the student's own AI. There is no server.
- **Feedback rules I wrote:** name specific points to improve instead of praise alone; never treat a speech-recognition error as the student's mistake; since the AI cannot hear the voice, give pronunciation advice as "try this" rather than "this is wrong"; at the end, ask the student what they found hardest and offer more help on that point.
- **My role:** I defined the problem, wrote the feedback rules, and tested the tool with students. The code was written with AI coding tools (Claude Code).
- **Status:** Tested with a small group of students in July 2026. Scheduled for use in a required speaking assessment for about 250 students in October–November 2026.
- **Known limitation:** The tool measures what is easy to measure (speaking rate, pitch range) rather than what the national curriculum asks students to achieve, such as conveying content accurately and supporting opinions with reasons.

---

**한국어 설명**

영어로 자유롭게 말하면, 내 AI(ChatGPT·Gemini)로 문법·표현·발음·억양 피드백을 받는 무료 웹 도구입니다.
고등학생 영어 말하기 연습용으로 만들었습니다.

## 어떻게 쓰나요
1. 사이트에 접속해 마이크를 허용합니다. (첫 방문 때 음성인식 프로그램을 한 번 내려받아요)
2. 영어로 자유롭게 말하고 정지합니다.
3. 들린 문장과 말하기 속도·억양·끊김이 화면에 나옵니다.
4. **ChatGPT 열기** 버튼을 누르면 피드백 요청이 채워진 채로 내 AI가 열립니다. (Gemini 등은 **프롬프트 복사** 후 붙여넣기)

## 특징
- **무료**입니다. 별도 계정이나 비용이 필요 없습니다.
- **목소리는 기기 밖으로 나가지 않습니다.** 음성인식은 브라우저 안에서 처리되고, 내 AI로는 받아쓴 문장 텍스트만 전달됩니다.
- 녹음은 **이 브라우저에만** 저장되어 다시 듣기·복습할 수 있습니다.

## 참고
- 마이크는 HTTPS 주소에서만 열립니다. (GitHub Pages는 자동 HTTPS)
- 음성인식이라 발음이 뭉개지면 잘못 들릴 수 있어요. 또박또박 말하면 정확도가 올라갑니다.
