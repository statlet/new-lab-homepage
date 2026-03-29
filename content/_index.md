---
title: Home
type: landing

sections:
  # 1. 메인 간판 (Hero 블록 부활 - 묵직하고 세련된 네이비 배경)
  - block: hero
    content:
      title: 'Statistical Learning Theory Lab'
      text: |
        **서울대학교 통계학과 통계적 학습이론 연구실에 오신 것을 환영합니다.**
        
        우리 연구실의 주요 연구 내용은 비정형 데이터 분석(non-standard data analysis)입니다. 구체적으로는 High-dimension low-sample size (HDLSS) problems, geometrical data, non-euclidean type data 들을 다루고 있으며, 이를 대상으로 PCA, classification, multisource data integration 등의 연구를 진행하고 있습니다.
    design:
      background:
        color: '#112240' # 학술적이고 무게감 있는 딥 네이비 색상
        text_color_light: true
      spacing:
        padding: ['100px', '0', '100px', '0']

  # 2. 최근 뉴스 (깔끔한 흰색 배경)
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

  # 3. 심플한 연락처 정보
  - block: markdown
    content:
      title: 'Contact Us'
      text: |
        <div style="display: flex; flex-wrap: wrap; gap: 30px; margin-top: 20px;">
          
          <div style="flex: 1; min-width: 250px; background-color: #f8fafc; padding: 25px; border-radius: 8px; border-left: 4px solid #112240;">
            <h3 style="margin: 0 0 5px 0; font-size: 1.2rem;">정성규 (Sungkyu Jung)</h3>
            <div style="color: #4b5563; font-size: 0.95rem; font-weight: 600; margin-bottom: 15px;">Director</div>
            <p style="margin: 0; font-size: 1rem;">📧 <a href="mailto:sungkyu@snu.ac.kr" style="color: #112240; text-decoration: none;">sungkyu@snu.ac.kr</a></p>
          </div>

          <div style="flex: 1; min-width: 250px; background-color: #f8fafc; padding: 25px; border-radius: 8px; border-left: 4px solid #475569;">
            <h3 style="margin: 0 0 5px 0; font-size: 1.2rem;">김규원</h3>
            <div style="color: #4b5563; font-size: 0.95rem; font-weight: 600; margin-bottom: 15px;">Lab Manager</div>
            <p style="margin: 0; font-size: 1rem;">📧 <a href="mailto:kwkim1224@snu.ac.kr" style="color: #475569; text-decoration: none;">kwkim1224@snu.ac.kr</a></p>
          </div>

        </div>
    design:
      columns: '1'
      css_class: 'vw55block' 
      spacing:
        padding: ['20px', '0', '80px', '0']
---
