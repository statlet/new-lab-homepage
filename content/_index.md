---
title: Home
type: landing

sections:
  # 1. 메인 간판 (hero 블록 대신 markdown 블록 사용 -> 높이/너비 문제 완벽 해결!)
  - block: markdown
    content:
      title: 'Statistical Learning Theory Lab'
      text: |
        **서울대학교 통계학과 통계적 학습이론 연구실에 오신 것을 환영합니다.**
        
        우리 연구실의 주요 연구 내용은 비정형 데이터 분석(non-standard data analysis)입니다. 구체적으로는 High-dimension low-sample size (HDLSS) problems, geometrical data, non-euclidean type data 들을 다루고 있으며, 이를 대상으로 PCA, classification, multisource data integration 등의 연구를 진행하고 있습니다.
    design:
      background:
        color: '#112240' # 딥 네이비 배경색
        text_color_light: true # 글자색을 자동으로 흰색으로 변경
      columns: '1'
      css_class: 'vw55block' # ⚠️ 우리가 만든 마법의 이름표! 이제 글자가 좌우로 시원하게 퍼집니다.
      spacing:
        padding: ['80px', '0', '80px', '0'] # 위아래 여백을 대폭 줄여서 배너처럼 만듦

  # 2. 최근 뉴스
  - block: markdown
    content:
      title: 'Recent News'
      text: |
        * **[2026-03-29]** 통계적 학습이론 연구실 홈페이지를 새롭게 단장했습니다.
        * **[2026-03-26]** 딥러닝을 주제로 한 연구실 세미나가 시작되었습니다.
        * **[2026-02-25]** 김용재 학생이 박사과정을, 김우열, 유지현 학생이 석사과정을 졸업하였습니다.
        
        [➔ View all news](/news/)
    design:
      columns: '1'
      css_class: 'vw55block' 
      spacing:
        padding: ['60px', '0', '20px', '0']

  # 3. 심플한 연락처 정보 (카드 형식 제거, 이상한 아이콘 제거)
  - block: markdown
    content:
      title: 'Contact Us'
      text: |
        <div style="display: flex; flex-wrap: wrap; gap: 40px; margin-top: 10px;">
          
          <div style="flex: 1; min-width: 250px;">
            <h3 style="margin: 0 0 5px 0; font-size: 1.2rem;">정성규 (Sungkyu Jung)</h3>
            <div style="color: #4b5563; font-size: 0.95rem; font-weight: 600; margin-bottom: 10px;">Director</div>
            <p style="margin: 0; font-size: 1rem;">Email: <a href="mailto:sungkyu@snu.ac.kr" style="color: #1e3a8a; text-decoration: none;">sungkyu@snu.ac.kr</a></p>
          </div>

          <div style="flex: 1; min-width: 250px;">
            <h3 style="margin: 0 0 5px 0; font-size: 1.2rem;">김규원</h3>
            <div style="color: #4b5563; font-size: 0.95rem; font-weight: 600; margin-bottom: 10px;">Lab Manager</div>
            <p style="margin: 0; font-size: 1rem;">Email: <a href="mailto:kwkim1224@snu.ac.kr" style="color: #1e3a8a; text-decoration: none;">kwkim1224@snu.ac.kr</a></p>
          </div>

        </div>
    design:
      columns: '1'
      css_class: 'vw55block' 
      spacing:
        padding: ['20px', '0', '80px', '0']
---
