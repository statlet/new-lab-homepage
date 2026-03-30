---
title: Research
type: landing
math: true  # ⚠️ 수학 기호(p, n) 렌더링을 위해 반드시 필요합니다!

sections:
  # 1. 페이지 메인 타이틀
  - block: markdown
    content:
      title: ''
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left; padding-bottom: 20px; border-bottom: 4px solid #112240;">
        <h1 style="margin: 0; font-size: 3rem; color: #112240; font-weight: 800; letter-spacing: -1px;">Research</h1>
        <p style="margin: 10px 0 0 0; font-size: 1.1rem; color: #6b7280;">통계적 학습이론 연구실의 주요 연구 분야를 소개합니다.</p>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['80px', '5%', '30px', '5%']

  # 2. HDLSS Problem
  - block: markdown
    content:
      title: ''
      text: |
        <div id="hdlss" style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left; padding-top: 80px; margin-top: -80px;">
        
        <div style="display: flex; flex-wrap: wrap; gap: 40px; align-items: flex-start;">
          <div style="flex: 1; min-width: 300px; max-width: 400px;">
            <img src="/research/hdlss.png" alt="HDLSS" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
          </div>
          
          <div style="flex: 2; min-width: 300px;">
            <h2 style="margin: 0 0 15px 0; font-size: 2rem; color: #112240;">High-Dimension Low-Sample-Size (HDLSS) Problem</h2>
            <div style="margin-bottom: 15px;">
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#HDLSS</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#PCA</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Data Piling</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-bottom: 5px;">#JIVE</span>
            </div>
            <p style="font-size: 1.05rem; line-height: 1.8; color: #374151;">고차원 저표본(High-Dimension, Low-Sample-Size; HDLSS) 데이터 분석은 변수의 수($p$)가 표본의 수($n$)보다 매우 큰 상황($p \gg n$)에서 발생하는 통계적 한계와 기하학적 특성을 다루는 연구 분야입니다. 기존의 다변량 통계 기법이 적용되기 어려운 이 환경에서는, 분류 시 데이터가 특정 부분공간이나 축에 집중되는 데이터 파일링(Data Piling) 현상이 관찰됩니다. 저희 연구실은 이러한 현상의 기하학적 구조를 규명하고, 고차원 주성분 분석(High-dimensional PCA)을 통해 차원 축소의 성능을 개선하는 방법론을 연구합니다. 또한, 다중 소스로부터 수집된 복잡한 데이터 블록을 분석하기 위해 JIVE(Joint and Individual Variation Explained) 기법을 활용합니다. 이를 통해 서로 다른 데이터 간의 공통된 구조(Joint variation)와 각 데이터 고유의 변동(Individual variation)을 분리함으로써, 차원이 크고 표본 확보가 제한적인 비정형 데이터에서도 보다 안정적이고 신뢰할 수 있는 통계적 추론을 수행하고자 합니다.</p>
          </div>
        </div>
        
        <hr style="border: 0; border-bottom: 1px solid #e5e7eb; margin: 60px 0;">
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '5%', '0', '5%']

  # 3. Non-euclidean data
  - block: markdown
    content:
      title: ''
      text: |
        <div id="non-euclidean" style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left; padding-top: 80px; margin-top: -80px;">
        
        <div style="display: flex; flex-wrap: wrap; gap: 40px; align-items: flex-start;">
          <div style="flex: 1; min-width: 300px; max-width: 400px;">
            <img src="/research/non_euclidean.png" alt="Non-euclidean" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
          </div>
          
          <div style="flex: 2; min-width: 300px;">
            <h2 style="margin: 0 0 15px 0; font-size: 2rem; color: #112240;">Non-Euclidean Data Analysis</h2>
            <div style="margin-bottom: 15px;">
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Non-Euclidean Statistics</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#OODA</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Generalized Fréchet Mean</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Compositional Data Analysis</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Shape & Image Analysis</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-bottom: 5px;">#Phylogenetic Tree Data Analysis</span>
            </div>
            <p style="font-size: 1.05rem; line-height: 1.8; color: #374151;">현대 통계학과 데이터 과학에서는 인체 마이크로바이옴 구성 비율(Compositional data), 물체의 방향(Direction) 및 형상(Shape) 등 비유클리드(Non-Euclidean) 구조를 가진 데이터의 중요성이 점차 커지고 있습니다. 이러한 데이터는 단순체(Simplex), 구면(Sphere), 사영 공간(Projective space)과 같은 리만 다양체(Riemannian manifold) 위에 존재하는 경우가 많아, 기존의 유클리드 기반 분석법을 적용하면 거리 척도나 공분산 구조가 심각하게 왜곡될 수 있습니다. 저희 연구실은 데이터의 내재적 기하 구조를 엄밀하게 보존하고 반영하는 객체 지향 데이터 분석(Object Oriented Data Analysis; OODA) 방법론을 개발하고 있습니다. 나아가 제안된 기하학적 통계 방법론의 신뢰성과 일관성을 수학적으로 증명하여, 복잡한 비정형 데이터 분석의 새로운 표준을 제시하고자 합니다.</p>
          </div>
        </div>
        
        <hr style="border: 0; border-bottom: 1px solid #e5e7eb; margin: 60px 0;">
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '5%', '0', '5%']

  # 4. Data Privacy
  - block: markdown
    content:
      title: ''
      text: |
        <div id="privacy" style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left; padding-top: 80px; margin-top: -80px;">
        
        <div style="display: flex; flex-wrap: wrap; gap: 40px; align-items: flex-start;">
          <div style="flex: 1; min-width: 300px; max-width: 400px;">
            <img src="/research/privacy.png" alt="Data Privacy" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
          </div>
          
          <div style="flex: 2; min-width: 300px;">
            <h2 style="margin: 0 0 15px 0; font-size: 2rem; color: #112240;">Data Privacy</h2>
            <div style="margin-bottom: 15px;">
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Differential Privacy</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Synthetic Data</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-bottom: 5px;">#Privacy-Utility Trade-off</span>
            </div>
            <p style="font-size: 1.05rem; line-height: 1.8; color: #374151;">빅데이터 시대에 개인정보 보호는 필수적인 윤리적, 법적 요구사항이 되었습니다. 하지만 데이터를 안전하게 보호하기 위해 변형을 가하면 통계적 유용성(utility)이 훼손되는 트레이드오프 관계에 놓이게 됩니다. 저희 연구실은 차분 프라이버시(Differential Privacy) 등 엄밀한 수학적 프라이버시 기준을 만족하면서도, 원본 데이터가 가진 통계적 특성을 최대한 보존하여 유의미한 추론을 가능하게 하는 방법론을 연구합니다. 특히 고차원 다변량 자료에 대한 프라이버시 보존 추론 및 재현 데이터(Synthetic Data) 생성 기술 개발에 주력하고 있습니다.</p>
          </div>
        </div>
        
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '5%', '80px', '5%']
---
