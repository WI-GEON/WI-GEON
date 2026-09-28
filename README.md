<!-- ============================ HEADER ============================ -->
<!-- 직접 만든 게임 스크린샷/픽셀아트로 교체 추천: assets/banner.png (1280x320 권장) -->
<p align="center">
  <img src="https://placehold.co/1280x320/0D1117/70A5FD/png?text=WI-GEON%0AUnity+Client+Developer" width="100%" alt="banner">
</p>

<p align="center">
  <a href="https://github.com/WI-GEON">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1200&color=70A5FD&center=true&vCenter=true&width=560&lines=Unity+%2F+C%23+Game+Client+Developer;Reverse-engineering+game+mechanics;From+analysis+to+playable+code" alt="typing">
  </a>
  <br>
  <img src="https://komarev.com/ghpvc/?username=WI-GEON&label=PROFILE+VIEWS&color=70A5FD&style=flat-square" alt="views">
</p>

<!-- ============================ PLAYER ============================ -->
### PLAYER

```
$ ./whoami --player

  NAME     : 위건 (WI-GEON)
  CLASS    : Unity Client Developer
  MAIN     : C#
  PLAYSTYLE: 게임 메커니즘 분석 → 직접 재구현
  STATUS   : 습작 2종 + CS 스터디 진행 중 (~ 2026.11)
  DEVLOG   : velog.io/@w_wgeon
```

좋은 조작감과 시스템이 **왜** 그렇게 동작하는지 분석하고, 직접 재구현하면서 이해합니다.  
코드는 이곳에, 분석과 설계 과정은 [Velog](https://velog.io/@w_wgeon)에 기록합니다.

<br>

<!-- ============================ LOADOUT ============================ -->
### LOADOUT

<p>
  <img src="https://skillicons.dev/icons?i=unity,cs,rider,visualstudio,git,github,notion&theme=dark" alt="stack">
</p>

| | |
| :-- | :-- |
| **Engine** | Unity 2022.3+ |
| **Language** | C# |
| **Tools** | Rider · Visual Studio · Git · GitHub |
| **Collaboration** | Jira · Confluence · Notion |

<br>

<!-- ============================ QUEST LOG ============================ -->
### QUEST LOG

<table>
  <tr>
    <td width="45%">
      <!-- 완성되면 플레이 GIF로 교체 -->
      <img src="https://placehold.co/560x315/0D1117/70A5FD/png?text=Tap-Strafe%0AGIF+coming+soon" width="100%">
    </td>
    <td>
      <b>Tap-Strafe</b> &nbsp;<img src="https://img.shields.io/badge/IN_PROGRESS-70A5FD?style=flat-square"><br>
      <sub>Apex Legends 무브먼트 분석 · 재현</sub><br><br>
      공중에서 짧은 입력을 연타하면 왜 속도를 잃지 않고 방향이 바뀌는가?<br><br>
      <sub>Repository coming soon</sub>
    </td>
  </tr>
  <tr>
    <td width="45%">
      <img src="https://placehold.co/560x315/0D1117/70A5FD/png?text=Unit-Pool%0AGIF+coming+soon" width="100%">
    </td>
    <td>
      <b>Unit-Pool</b> &nbsp;<img src="https://img.shields.io/badge/IN_PROGRESS-70A5FD?style=flat-square"><br>
      <sub>오토배틀러 서버 권한 기물 분배</sub><br><br>
      모두가 공유하는 기물 풀에서 확률과 재고를 어디서, 어떻게 관리해야 하는가?<br><br>
      <sub>Repository coming soon</sub>
    </td>
  </tr>
</table>

<details>
<summary><b>Tap-Strafe</b> — 분석 노트 펼치기</summary>
<br>

**질문** &nbsp;공중 연타 입력이 속도를 유지한 채 방향을 꺾는 원리  
**접근** &nbsp;프레임 단위 공중 가속 계산을 분석하고, 입력 빈도·프레임레이트에 따른 속도 변화를 측정  
**결과** &nbsp;<!-- 비교 GIF / 속도 그래프 -->

</details>

<details>
<summary><b>Unit-Pool</b> — 분석 노트 펼치기</summary>
<br>

**질문** &nbsp;공용 기물 풀과 확률 테이블을 누가 소유해야 하는가  
**접근** &nbsp;서버가 풀과 확률 테이블을 소유하고, 클라이언트는 결과만 받는 구조로 구현  
**결과** &nbsp;<!-- 구조도 / 시연 GIF -->

</details>

<details>
<summary><b>CS-Study</b> — 자료구조 · 알고리즘 · 컴퓨터구조 · 운영체제</summary>
<br>

| 저장소 | 내용 |
| :-- | :-- |
| [dsa-notes](https://github.com/WI-GEON/dsa-notes) | 자료구조 · 알고리즘 문제 풀이와 오답 노트 |
| [CodingTest](https://github.com/WI-GEON/CodingTest) | 코딩 테스트 풀이 (C#) |

</details>

<br>

<!-- ============================ DEV LOG ============================ -->
### DEV LOG

<!-- Velog 최신 글이 GitHub Actions로 자동 갱신됩니다 -->
<!-- BLOG-POST-LIST:START -->
- [[VS] 참조 표시 제거](https://velog.io/@w_wgeon/VS-%EC%B0%B8%EC%A1%B0-%ED%91%9C%EC%8B%9C-%EC%A0%9C%EA%B1%B0)
- [오버플로우와 언더플로우 &lpar;Overflow &amp; Underflow&rpar;](https://velog.io/@w_wgeon/OverflowUnderflow)
- [박싱과 언박싱 &lpar;Boxing &amp; Unboxing&rpar;](https://velog.io/@w_wgeon/BoxingUnboxing)
- [🎮 Game Start!](https://velog.io/@w_wgeon/%EA%B2%8C%EC%9E%84-%EA%B0%9C%EB%B0%9C%EC%9E%90%EB%A1%9C%EC%84%9C%EC%9D%98-%EC%83%88%EB%A1%9C%EC%9A%B4-%EC%8B%9C%EC%9E%91)
<!-- BLOG-POST-LIST:END -->

<br>

<!-- ============================ STATS ============================ -->
### STATS

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=WI-GEON&show_icons=true&hide_border=true&hide_title=true&bg_color=0D1117&icon_color=70A5FD&text_color=C9D1D9&cache_seconds=86400" height="150">
  <img src="https://streak-stats.demolab.com?user=WI-GEON&hide_border=true&background=0D1117&ring=70A5FD&fire=70A5FD&currStreakLabel=70A5FD&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=8B949E&dates=6E7681" height="150">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/WI-GEON/WI-GEON/output/snake-dark.svg">
    <img src="https://raw.githubusercontent.com/WI-GEON/WI-GEON/output/snake.svg" alt="contribution snake">
  </picture>
</p>

<br>

<!-- ============================ CONTACT ============================ -->
### CONTACT

<p>
  <a href="mailto:wigeon.dev@gmail.com"><img src="https://img.shields.io/badge/Email-wigeon.dev@gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=70A5FD"></a>
  <a href="https://velog.io/@w_wgeon"><img src="https://img.shields.io/badge/Velog-@w__wgeon-0D1117?style=for-the-badge&logo=velog&logoColor=70A5FD"></a>
</p>

<sub>실무 프로젝트는 계약상 비공개입니다. 포트폴리오는 요청 시 전달드립니다.</sub>
