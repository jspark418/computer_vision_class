1. 아래논문 및 github 코드 사용
- 논문 : Learning and Evaluating Representations for Deep One-Class Classification(https://arxiv.org/pdf/2011.02578.pdf)
- github 주소 : https://github.com/google-research/deep_representation_one_class

2. 사용 방법
- run_contrastive_da.sh 에서 하이퍼파라미터 설정 후 command 창에서 sh run_contrastive_da.sh 입력
- 결과 폴더 생성되어 저장됨

3. 개선사항
- optimizer 추가 : 사용 가능 optimizer [SGD(기본), SGDP, Adam, AdamP, LARS]
- model 추가 중 : 기본 모델 Resnet, EfficientNet 추가 중 

