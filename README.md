<img align="right" width="340" alt="cat coding on a laptop" src="./assets/cat-light.svg#gh-light-mode-only">
<img align="right" width="340" alt="cat coding on a laptop" src="./assets/cat-dark.svg#gh-dark-mode-only">

# 딴짓하는 류주임 🐱

**Public servant by day, MCP builder by night.**

낮엔 공문 결재하는 공무원, 밤엔 Claude랑 MCP 서버를 찍어냅니다.<br>
한국 공공데이터를 API로 뚫고,<br>
아무도 안 건드리던 HWP를 파싱하고,<br>
법령을 AI로 검색되게 만드는 중.

`Public AX FDE` &nbsp;·&nbsp; 공공영역에 AI 심기

[![Blog](https://img.shields.io/badge/blog-chris.gomdori.app-111111?style=flat-square)](https://chris.gomdori.app)
[![Threads](https://img.shields.io/badge/Threads-@chris__gomdori-111111?style=flat-square&logo=threads&logoColor=white)](https://www.threads.com/@chris_gomdori)
[![Stars](https://img.shields.io/github/stars/chrisryugj?style=flat-square&label=stars&color=D4472F&labelColor=111111)](https://github.com/chrisryugj)

## A little more about me...

```js
const gomdori = {
  role: "Public AX FDE",
  based: "Seoul, Korea 🇰🇷",
  code: ["TypeScript", "Rust", "Python"],
  stack: ["Claude Code", "MCP", "Vercel", "HWPX"],
  building: {
              publicData: ["korean-law-mcp", "korean-stats-mcp", "korean-dart-mcp",
                           "archhub-mcp", "korean-patent-mcp", "schoolinfo-mcp"],
              docParsing: ["kordoc", "kordoc-ai", "docufinder"],
                aiSearch: ["lexdiff"],
              agentTools: ["fable-ish", "hermes-dashboard", "ollama-mcp-host"],
            },
  funFact: "GitHub 별 5,600+개가 전부 딴짓의 산물 😼",
};
```

## What I'm building

<table width="100%">
<tr>
  <td width="180"><a href="https://github.com/chrisryugj/korean-law-mcp"><b>korean-law-mcp</b></a></td>
  <td width="72" align="right">★&nbsp;<!--stars:korean-law-mcp-->2.5k<!--/stars--></td>
  <td>법제처 국가법령정보 MCP. 법령·판례·조례 + 인용 환각 검증</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/kordoc"><b>kordoc</b></a></td>
  <td align="right">★&nbsp;<!--stars:kordoc-->1.8k<!--/stars--></td>
  <td>모두 파싱해버리겠다. HWP·HWPX·PDF·Office → Markdown</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/Docufinder"><b>Docufinder</b></a></td>
  <td align="right">★&nbsp;<!--stars:Docufinder-->652<!--/stars--></td>
  <td>파일을 찾지 말고, 내용을 찾으세요. 로컬 문서 본문 검색</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/korean-dart-mcp"><b>korean-dart-mcp</b></a></td>
  <td align="right">★&nbsp;<!--stars:korean-dart-mcp-->100<!--/stars--></td>
  <td>OpenDART 전자공시 MCP. 83개 API → 15개 도구, 재무·지분·첨부까지</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/korean-stats-mcp"><b>korean-stats-mcp</b></a></td>
  <td align="right">★&nbsp;<!--stars:korean-stats-mcp-->94<!--/stars--></td>
  <td>KOSIS 통계 MCP. 이제 사이트에 들어가지 않습니다</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/kordoc-ai"><b>kordoc-ai</b></a></td>
  <td align="right">★&nbsp;<!--stars:kordoc-ai-->76<!--/stars--></td>
  <td>HWP·PDF·Office 변환·요약·비교·병합 데스크톱 앱</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/archhub-mcp"><b>archhub-mcp</b></a></td>
  <td align="right">★&nbsp;<!--stars:archhub-mcp-->66<!--/stars--></td>
  <td>국토부 건축HUB MCP. 건축물대장·인허가·노후건축물 분석</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/korean-patent-mcp"><b>korean-patent-mcp</b></a></td>
  <td align="right">★&nbsp;<!--stars:korean-patent-mcp-->54<!--/stars--></td>
  <td>KIPRIS 특허·상표·디자인 검색 MCP</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/schoolinfo-mcp"><b>schoolinfo-mcp</b></a></td>
  <td align="right">★&nbsp;<!--stars:schoolinfo-mcp-->43<!--/stars--></td>
  <td>학교알리미 MCP. 급식·학생수·수행평가 계획 조회</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/fable-ish"><b>fable-ish</b></a></td>
  <td align="right">★&nbsp;<!--stars:fable-ish-->40<!--/stars--></td>
  <td>Claude Code 검증 게이트. 검증 전엔 done이라 말하지 않는다</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/hermes-dashboard"><b>hermes-dashboard</b></a></td>
  <td align="right">★&nbsp;<!--stars:hermes-dashboard-->39<!--/stars--></td>
  <td>Hermes Agent 게이트웨이 웹 대시보드. CLI 없이 설정·MCP·크론 관리</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/ollama-mcp-host"><b>ollama-mcp-host</b></a></td>
  <td align="right">★&nbsp;<!--stars:ollama-mcp-host-->22<!--/stars--></td>
  <td>로컬 Ollama로 MCP 서버 여러 개 동시 구동. 내부망·오프라인</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/edoc-summarizer"><b>edoc-summarizer</b></a></td>
  <td align="right">★&nbsp;<!--stars:edoc-summarizer-->15<!--/stars--></td>
  <td>서울시 전자문서 AI 요약 Edge 확장</td>
</tr>
<tr>
  <td><a href="https://github.com/chrisryugj/lexdiff"><b>lexdiff</b></a></td>
  <td align="right">★&nbsp;<!--stars:lexdiff-->9<!--/stars--></td>
  <td>한국 법령 AI 검색. 자연어 질문 → 원문 근거 답변</td>
</tr>
</table>

<sub>One must imagine a public servant happy. &nbsp;·&nbsp; 딴짓은 멈추지 않는다.</sub>
