## 5조: 2024년 5월 2일 20시 미팅

5조는 "드론영상을 이용한 콘크리트 댐의 크랙추출 방법"이라는 주제에 따라서 프로세스에 대한 이해와 Solution(안) 도출을 잘 했다고 생각합니다.
다음으로는 실제 조별로 실행가능한 범위의 주제를 정해서 분석을 해보는 절차를 진행했으면 합니다.

- Q-1: 드론을 활용한 영상의 촬영이 가능한가? 가능하다면 어느 정도의 해상도로 촬영이 가능한가?

- Q-2: 정사영상을 활용한 3D 모델링은 가능한가?

- Q-3: 콘크리트댐의 균열사진을 얻을 수 있는가? 또한 학습을 할수 있을 정도의 많은 콘크리트댐 균열사진을 얻을 수 있는가?

- Q-4: 콘크리트댐의 균열사진을 얻을 수 없다면, 콘크리트댐의 균열이나 그외 콘크리트의 균열을 Detecting할 수 있는 Pretrained된 모델을 얻을 수 있는가?

- Q-5: AI알고리즘으로 제시한 Faster R-CNN은 활용이 가능한가?

 **위의 Questions에서 현실적으로 실행가능한 주제는 어떤 것이 있을까요?**

### Recomentation for Mid-Term Report

1. Project website for Segmentation anything of Meta: https://segment-anything.com/
   
2. Segmentation Anything관련 Youtube 영상
   - https://www.youtube.com/watch?v=KQ3haqbIaSk
   - https://www.youtube.com/watch?v=HSBb9ImSohA
     
3. 실습 Site
   - **(Segmentation Anything Demo Website)** https://segment-anything.com/demo
   - **(Huggingface Spaces Segmentation Anything)** https://huggingface.co/spaces/Xenova/segment-anything-web
   - **(Huggingface Spaces Demo)** https://huggingface.co/spaces/sam-hq-team/sam-hq
  
   - **(Recognize Anything Model)** https://huggingface.co/spaces/xinyu1205/recognize-anything

   - **(Large Language and Vision Assistant)** https://llava.hliu.cc/    Prompts: Segment cracks on concrete
     
   - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Water-AI-Capstone-Design-KM-Univ/segment-anything.git/HEAD) The use of CPU has kernel kill problem on Jupyter notebook in Binder environment.
