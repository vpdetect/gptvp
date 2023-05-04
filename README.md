# 초거대 언어모델을 활용한 실시간 보이스피싱 탐지 기법

1. 실험 데이터의 녹취록 원본 파일들은 원본데이터 셋 폴더 안에 있습니다.
OpenAI를 실험에 사용하기 위해선 openai를 설치하셔야 합니다.
URL은 다음과 같습니다. https://platform.openai.com/docs/api-reference/introduction

2. OpenAI의 API를 사용하기 위해선 API 키를 개인적으로 발급받아야 합니다. 이를 생성하기 위해서 Google에 openai api key 발급을 검색한 뒤 따라 하시면 API키를 생성하실 수 있습니다. 이를 Real-time Voice Phishing Detection.py 파일의 4번째 줄에 수정하시면 됩니다.

3. 주피터 노트북 파일 폴더에 있는 파일을 실행할 떄 error가 발생한다면 파일의 경로를 절대경로로 바꾸어 주시길 바랍니다.

4. 코랩 업로드 폴더의 KoBERT를 구글 드라이브에 업로드하여 실행하시길 바랍니다. 실행 시 데이터의 경로와 GPU 환경을 확인 하시길 바랍니다. 데이터 경로 오류와 GPU 환경에 의해 에러가 자주 발생합니다.
선행 연구의 전체 코드는 https://github.com/selfcontrol7/Korean_Voice_Phishing_Detection 에서 다운받으실 수 있습니다.
