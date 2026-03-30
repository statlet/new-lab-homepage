---
title: Home
type: landing

sections:
  # 1. 메인 간판 (Navy & 가독성 개선)
  - block: markdown
    content:
      title: '' 
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h1 style="color: white; font-size: 2.5rem; margin-bottom: 20px;">Statistical Learning Theory Lab</h1>
        <div style="font-size: 1.1rem; line-height: 1.8; color: white;">
        <p><strong style="color: white;">서울대학교 통계학과 통계적 학습이론 연구실에 오신 것을 환영합니다.</strong></p>
        <p>우리 연구실의 주요 연구 내용은 비정형 데이터 분석(non-standard data analysis)입니다. 구체적으로는 High-Dimension Low-Sample-Size (HDLSS) problems, Non-Euclidean Data, Data Privacy 등을 다루고 있으며, 이를 대상으로 PCA, classification, multisource data integration 등의 연구를 진행하고 있습니다.</p>
        </div>
        </div>
    design:
      background:
        # 👇 가독성 개선을 위해 이미지 주소 뒤에 'rgba' 투명 마스크를 추가했습니다.
        image:
          filename: home-banner.jpg # banner.jpg 폴더의 이미지
          filters:
            brightness: 0.5 # 이미지 밝기를 50%로 낮춤 (CSS filter 지원하는 테마만)
          # filters가 안 먹히는 테마를 위해 rgba 마스크 추가
          overlay:
            color: 'rgba(17, 34, 64, 0.7)' # 70% 투명도의 Navy 마스크
      columns: '1'
      spacing:
        padding: ['100px', '5%', '100px', '5%']

  # 2. Research Interests (사진 대폭 확대)
  - block: markdown
    content:
      title: ''
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h2 style="margin: 0 0 10px 0; font-size: 2rem; color: #112240;">Research Interests</h2>
        <hr style="border: 0; border-bottom: 2px solid #e5e7eb; margin-bottom: 40px; width: 100%;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 30px;">
        
        <div style="flex: 1; min-width: 280px; max-width: 310px;">
        <img src="/research/hdlss.png" alt="High-dimension low-sample-size" style="height: 160px; margin-bottom: 25px; object-fit: contain;">
        <h3 style="font-size: 1.25rem; margin: 0 0 10px 0; color: #1e3a8a;">HDLSS</h3>
        <p style="font-size: 0.95rem; color: #4b5563; line-height: 1.6;">고차원 저표본(High-Dimension, Low-Sample-Size) 상황에서 발생하는 통계적 한계를 극복하는 방법론 연구</p>
        </div>
        
        <div style="flex: 1; min-width: 280px; max-width: 310px;">
        <img src="/research/non_euclidean.png" alt="Non-euclidean" style="height: 160px; margin-bottom: 25px; object-fit: contain;">
        <h3 style="font-size: 1.25rem; margin: 0 0 10px 0; color: #1e3a8a;">Non-Euclidean Data</h3>
        <p style="font-size: 0.95rem; color: #4b5563; line-height: 1.6;">다양체, 트리, 그래프 등 비유클리드 공간에 존재하는 데이터의 통계적 분석</p>
        </div>
        
        <div style="flex: 1; min-width: 280px; max-width: 310px;">
        <img src="/research/privacy.png" alt="Data Privacy" style="height: 160px; margin-bottom: 25px; object-fit: contain;">
        <h3 style="font-size: 1.25rem; margin: 0 0 10px 0; color: #1e3a8a;">Data Privacy</h3>
        <p style="font-size: 0.95rem; color: #4b5563; line-height: 1.6;">데이터 프라이버시를 보존하면서도 유의미한 통계적 추론을 수행하는 기법 개발</p>
        </div>
        
        </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['80px', '5%', '60px', '5%']

  # 3. 최근 뉴스
  - block: markdown
    content:
      title: ''
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h2 style="margin: 0 0 10px 0; font-size: 2rem; color: #112240;">Recent News</h2>
        <hr style="border: 0; border-bottom: 2px solid #e5e7eb; margin-bottom: 30px; width: 100%;">
        <div style="line-height: 2; font-size: 1.05rem; color: #374151;">
        <div style="margin-bottom: 10px;"><strong>[2026-03-29]</strong> 통계적 학습이론 연구실 홈페이지를 새롭게 단장했습니다.</div>
        <div style="margin-bottom: 10px;"><strong>[2026-03-26]</strong> 딥러닝을 주제로 한 연구실 세미나가 시작되었습니다.</div>
        <div style="margin-bottom: 10px;"><strong>[2026-02-25]</strong> 김용재 학생이 박사과정을, 김우열, 유지현 학생이 석사과정을 졸업하였습니다.</div>
        </div>
        <div style="margin-top: 25px;">
        <a href="/news/" style="text-decoration: none; color: #1e3a8a; font-weight: bold;">➔ View all news</a>
        </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['40px', '5%', '60px', '5%']

  # 4. 연락처
  - block: markdown
    content:
      title: ''
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h2 style="margin: 0 0 10px 0; font-size: 2rem; color: #112240;">Contact Us</h2>
        <hr style="border: 0; border-bottom: 2px solid #e5e7eb; margin-bottom: 30px; width: 100%;">
        <div style="display: flex; flex-direction: column; gap: 30px; color: #374151;">
        <div>
        <h3 style="margin: 0 0 5px 0; font-size: 1.25rem; color: #112240;">정성규 <span style="font-size: 1rem; color: #6b7280; font-weight: normal; margin-left: 5px;">| Professor</span></h3>
        <p style="margin: 0; font-size: 1.05rem;">Email: sungkyu@snu.ac.kr</p>
        </div>
        <div>
        <h3 style="margin: 0 0 5px 0; font-size: 1.25rem; color: #112240;">김규원 <span style="font-size: 1rem; color: #6b7280; font-weight: normal; margin-left: 5px;">| Lab Manager</span></h3>
        <p style="margin: 0; font-size: 1.05rem;">Email: kwkim1224@snu.ac.kr</p>
        </div>
        </div>
        </div>
    design:
      background:
        color: '#f8fafc' 
      columns: '1'
      spacing:
        padding: ['60px', '5%', '80px', '5%']
---
