# NLP-study

### Topic
<hr/>
대화형 인공지능 챗봇을 통한 위로 맥락에서의 감성분석

### Summary
<hr/>
본 연구에서는 사용자가 위로가 필요한 특정 감정을 가지고 대화할 때, 대화형 인공지능 챗봇이 해당하는 감정에 알맞게 반응하며 소통할 수 있는지에 대해 알아보는 것을 목적으로 Pretrained KoBERT 모델을 활용하여 사람문장과 시스템문장을 입력하였을 때, 이 두 문장의 관계가 어떤 감정에 해당하는지 분류해주는 모델을 개발함.



-> 대화형 인공지능 챗봇 : chat GPT 사용

-> KcBERT 사용 : Korean commnet BERT

-> 두 문장 관계 분류를 위한 문장 쌍 분류 task + 감성분석을 위한 문서분류 task

### Goal
<hr/>
대화형 인공지능 챗봇이 상황에 맞는 감정적인 위로를 하며 인간과 소통할 수 있는지에 대해 현황을 분석하고자 함.


### result
<hr/>
사람 문장과 시스템 문장 두 문장을 각각 토큰화 한 뒤 [CLS] + 사람문장 + [SEP] + 시스템문장 + [SEP] 형태로 이어 붙임
![image](https://user-images.githubusercontent.com/100950656/223349249-1c7584ab-dcc4-45ca-a2ad-118ea74f34e1.png)

![image](https://user-images.githubusercontent.com/100950656/223348433-0464125e-4863-4896-977b-c6f2ab708196.png)

평가
![image](https://user-images.githubusercontent.com/100950656/223348506-1b2d4109-8bfb-4c05-bd40-47b161d2d833.png)

![image](https://user-images.githubusercontent.com/100950656/223348571-063a51f2-0d93-465e-a43d-517449eaeb1f.png)

![image](https://user-images.githubusercontent.com/100950656/223348530-2cb12c3f-ce9e-44ff-9aef-a79d3a069465.png)
