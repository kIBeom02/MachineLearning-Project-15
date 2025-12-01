# 머신러닝_미니프로젝트_15조
KoGPT2와 LoRA를 활용한 F/T 성향 챗봇

학습은 코랩으로 진행했습니다

핵심 기능:

F-Bot (공감형): 사용자의 감정을 읽고 위로와 공감을 건네는 대화 모델

T-Bot (상담형): 사용자의 고민을 분석하고 논리적인 해결책을 제시하는 상담 모델

실시간 전환: 대화 중 `!변경` 명령어를 통해 즉시 성격 전환 가능

1. F-Bot (공감형) 학습
데이터셋: 감성 대화 말뭉치 https://www.aihub.or.kr/aihubdata/data/view.do?pageIndex=2&currMenu=115&topMenu=100&srchOptnCnd=OPTNCND001&searchKeyword=%EA%B0%90%EC%84%B1&srchDetailCnd=DETAILCND001&srchOrder=ORDER001&srchPagePer=20&aihubDataSe=data&dataSetSn=86
2. T-Bot (상담형) 학습
데이터셋: 심리 상담 데이터 https://www.aihub.or.kr/aihubdata/data/view.do?srchOptnCnd=OPTNCND001&currMenu=115&topMenu=100&searchKeyword=%EC%8B%AC%EB%A6%AC%EC%83%81%EB%8B%B4&aihubDataSe=data&dataSetSn=71806

F-Bot (공감형) 평가
<img width="1237" height="455" alt="스크린샷 2025-12-02 012923" src="https://github.com/user-attachments/assets/f0741132-685c-444c-b00f-061459b38ead" />

T-Bot (상담형) 평가
<img width="1204" height="453" alt="스크린샷 2025-12-02 012446" src="https://github.com/user-attachments/assets/32c6bed2-7128-450a-a559-34678bbfa06d" />

