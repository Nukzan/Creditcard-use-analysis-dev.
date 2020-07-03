# Creditcard-use-analysis-dev
AI 알고리즘 활용 카드 사용 금액 예측 (Dacon 경진대회) - https://dacon.io/competitions/official/235615/overview/

## 1. 배경
- 신용카드 사용량을 분석을 통한  ‘Post COVID-19 시대’ 신용카드 사용량 예측 모델 개발
- 지역 경제 위축 및 중소상공인 경영난 해소를 위한 대책 마련

## 2. 목적
- 신용카드 사용 내역 데이터를 활용한 지역별, 업종별 월간 카드 사용 총액 예측

## 3. 주최/주관
- 주최 : 제주특별자치도청, 제주테크노파크
- 주관 : DACON

## 4. 규칙
 #### 1) 평가식
 - RMSLE (Root Mean Square Logarithmic Error) 
 - 제주 지역에 3배 가중치 부여
 
 #### 2) 평가
 - 가채점 순위 (Public Score) : 1차 테스트 데이터 (2020.04) 로 채점
 - 최종 순위 (Private Score) : 2차 테스트 데이터 (2020.07) 로 채점, 대회 종료 후 공개
 - 최종 순위는 선택된 파일 중에서 채점되므로, 참가자는 제출 창에서 자신이 최종적으로 채점 받고 싶은 파일을 선택해야 함. (최종 파일 미선택시 처음으로 제출한 파일로 자동 선택됨)
 - 리더보드 운영 종료 이후 Private Score 랭킹이 가장 높은 참가자 5팀은 양식에 맞는 코드와 함께 코드 내용을 설명하는 PPT 제출 (대회 종료 후 dacon@dacon.io를 통해 안내)
 - 대회 직후 공개되는 Private Score 랭킹은 최종 순위가 아니며 코드 검증 후 최종 수상자가 결정됨

 #### 3) 외부 데이터
 - 공공 데이터와 같은 법적인 제약이 없는 경우에만 사용 가능
 - 공공데이터 다운을 받은 경우 링크를 게시해야 함
 - 크롤링 시 코드 제출 필수
 - 2020.04.30 데이터까지만 사용 가능

 #### 4) 개인 및 팀 병합 규정
 - 개인 참가 방법 : 팀 신청 없이, 자유롭게 제출 창에서 제출 가능 
 - 팀 참가 방법 : 팀 배너에서 가능, 상세 내용은 팀 배너에서 팀 병합 정책 확인
 - 하나의 대회에는 하나의 팀으로만 등록 가능
 - 팀 병합 후 해체 및 개인 참가 불가
 - 팀의 수상 요건 충족 시 팀의 대표가 수상

 #### 5) 코드 제출 규칙
 - 입상자는 데이콘에서 안내한 양식에 맞추어 코드 제출
 - R user는 R or .rmd. Python user는 .py or .ipynb로 제출
 - 코드에 ‘/data’ 데이터 입/출력 경로 포함
 - 전체 프로세스를 가독성 있게 정리하여 주석 포함 하나의 파일로 제출
 - 제출 코드는 리더보드 점수를 복원할 수 있어야 함
 - 모든 코드는 오류 없이 실행되어야 함 (라이브러리 로딩 코드 포함)
 - 코드와 주석의 인코딩은 UTF-8 사용
