# Typing Flow — v17

## Fixes
- 입력 중 하단 정보가 늘어나도 버튼 행이 그래프 영역으로 내려가지 않도록 고정
- Reset / Copy All / Finish 클릭 영역을 그래프보다 높은 레이어로 고정
- 그래프 canvas가 마우스 이벤트를 가로채지 않도록 수정
- Copy All에 Clipboard API + 두 단계 fallback 적용
- 로컬 HTML과 GitHub Pages 모두 고려한 복사 로직

GitHub Pages에서는 `index.html`을 기존 파일과 교체하면 됩니다.
