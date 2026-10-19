# 수업 설계 스튜디오

학년, 과목, 성취기준 또는 수업 주제를 입력하면 Gemini API로 5단계 수업 지도안 초안을 생성하는 단일 페이지 앱입니다.

## Vercel 배포

1. GitHub에서 이 저장소를 Vercel 프로젝트로 가져옵니다.
2. Framework Preset은 **Other**를 선택하고 Root Directory는 저장소 루트로 둡니다.
3. 빌드 명령과 출력 디렉터리는 지정하지 않습니다. `index.html`이 루트 페이지로 직접 제공됩니다.
4. 배포가 끝나면 프로젝트 URL을 열어 Gemini API 키로 생성 기능을 확인합니다.

이 앱은 브라우저에서 Google Gemini API를 직접 호출합니다. API 키는 앱 화면에서 사용자가 입력하며, 페이지를 새로고침하면 유지되지 않습니다. 키를 HTML 소스나 공개 저장소에 넣지 마세요.

모델: `gemini-3.5-flash-lite`
