---
title: Research
type: landing

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
        <div id="hdlss" style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left; padding-top: 80px; margin-top: -80px;"> <div style="display: flex; flex-wrap: wrap; gap: 40px; align-items: flex-start;">
          <div style="flex: 1; min-width: 300px; max-width: 400px;">
            <img src="/research/hdlss.png" alt="HDLSS" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
          </div>
          
          <div style="flex: 2; min-width: 300px;">
            <h2 style="margin: 0 0 15px 0; font-size: 2rem; color: #112240;">High-Dimension Low-Sample-Size (HDLSS) Problem</h2>
            <div style="margin-bottom: 15px;">
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#High-Dimensional Statistics</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#PCA</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-bottom: 5px;">#Classification</span>
            </div>
            <p style="font-size: 1.05rem; line-height: 1.8; color: #374151;">고차원 저표본(HDLSS) 데이터 분석은 현대 통계학의 주요 과제 중 하나입니다. 변수의 수(dimension)가 표본의 수(sample size)보다 압도적으로 많은 상황에서는 전통적인 통계 방법론들이 작동하지 않는 현상(Curse of Dimensionality)이 발생합니다. 우리 연구실은 이러한 한계를 극복하기 위해, 데이터가 가지고 있는 내재적 구조(intrinsic structure)를 파악하고 차원을 효과적으로 축소하는 새로운 통계적 학습 이론과 알고리즘을 개발하고 있습니다. 특히 주성분분석(PCA)의 고차원 성질 연구 및 다양한 분류(classification) 문제에 응용하는 연구를 수행합니다.</p>
          </div>
        </div>
        
        <hr style="border: 0; border-bottom: 1px solid #e5e7eb; margin: 60px 0;">
        </div>

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
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Manifold Data</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Directional Statistics</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-bottom: 5px;">#Shape Analysis</span>
            </div>
            <p style="font-size: 1.05rem; line-height: 1.8; color: #374151;">현대의 많은 데이터는 평평한 유클리드 공간이 아닌 곡면이나 구면과 같은 비유클리드(Non-Euclidean) 공간, 또는 트레나 그래프 구조 위에 존재합니다. 방향 데이터(directional data), 형태 데이터(shape data), 대칭 행렬 데이터 등이 그 예입니다. 이러한 데이터에 기존의 유클리드 통계 기법을 적용하면 심각한 오류가 발생할 수 있습니다. 우리는 기하학적 통찰을 바탕으로 다양체(manifold) 공간 위에서 정의되는 올바른 평균, 분산, 상관관계를 정의하고, 이를 바탕으로 한 비유클리드 데이터 분석 방법론을 활발히 연구하고 있습니다.</p>
          </div>
        </div>
        
        <hr style="border: 0; border-bottom: 1px solid #e5e7eb; margin: 60px 0;">
        </div>

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
            <h2 style="margin: 0 0 15px 0; font-size: 2rem; color: #112240;">Data Privacy and Inference</h2>
            <div style="margin-bottom: 15px;">
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Differential Privacy</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-right: 5px; margin-bottom: 5px;">#Synthetic Data</span>
              <span style="display: inline-block; background-color: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 20px; font-size: 0.85rem; margin-bottom: 5px;">#Robust Statistics</span>
            </div>
            <p style="font-size: 1.05rem; line-height: 1.8; color: #374151;">데이터 프라이버시의 현대적 해법인 재현 자료(Synthetic Data)와 차분 프라이버시(Differential Privacy)는 데이터의 활용성(utility)과 노출 위험(disclosure risk)라는 상충하는 가치를 동시에 충족시키기 위한 핵심 기술입니다. 재현 자료가 실제 데이터의 통계적 특성을 모방하여 개인 식별 위험이 없는 가상의 정보를 생성해 데이터 활용의 폭을 넓힌다면, 차분 프라이버시는 데이터셋에 수학적인 노이즈를 추가하여 특정 개인의 정보가 분석 결과에 노출되지 않도록 철저히 방어합니다. 즉, 원본 데이터와 유사한 가짜 데이터를 만드는 방식과 결과값에 노이즈를 섞어 추론을 방해하는 방식의 결합은, 민감한 정보를 안전하게 다루어야 하는 AI 학습과 빅데이터 분석 환경에서 개인을 보호하면서도 통찰을 얻어낼 수 있는 가장 강력한 보안 패러다임을 제시합니다.</p>
          </div>
        </div>
        
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '5%', '80px', '5%']
---
