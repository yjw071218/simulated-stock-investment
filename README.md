# 모의 주식 투자 시뮬레이션 프로그램

- [설명서](./instruction.md)

## 소개
본 프로그램은 사용자가 가상의 주식 시장에서 투자 활동을 시뮬레이션할 수 있는 모의 주식 시뮬레이션 시스템입니다. 주식 시장의 동적 변동을 반영하여 경제 지표와 뉴스 이벤트에 따라 주가가 변동되며, 사용자는 다양한 전략을 통해 투자 성과를 평가할 수 있습니다.

## 주요 기능
1. **시장 시뮬레이션**
   - 경제 상황, 정책 변화, 특별 이벤트 등 다양한 요인이 시장에 영향을 미침.
   - 시뮬레이션의 30분 마다 경제 지표 업데이트.

2. **회사 관리**
   - 무작위로 생성된 회사들에 대한 주식 거래 가능.
   - 회사의 재무 정보 및 주가 변동 추적.
   - 파산 여부 및 계약, 퉅자 등의 상호작용 이벤트 지원.

3. **투자 전략**
   - 플레이어 및 봇 투자자 관리.
   - 봇은 랜덤, 성장, 섹터 집중, 가치, 모멘텀 전략 적용.
   - 포트폴리오 관리 및 손익 분석.

4. **차트 및 시각화**
   - 주가 변동을 캔들스틱 차트로 시각화.
   - 이동 평균선(MA) 제공.
   - 정세 및 경제 지표 시각화.

5. **뉴스 및 이벤트 시스템**
   - 정책 변화, 경제 뉴스, 자연재해, 정치적 사건 등 다양한 뉴스 제공.
   - 뉴스에 따라 개별 회사 또는 시장 전체에 영향 적용.

6. **목표 기반 시뮬레이션**
   - 초기 자금 2500만 원 지급
   - 90일 내 1억 원 달성 목표 설정.
   - 달성 여부에 따른 성공/실패 메시지 및 재시작 기능 지원.

## 설치 방법
1. **Python 설치**
   - Python 3.8 이상이 필요합니다.

2. **필수 라이브러리 설치**
   ```bash
   pip install pygame
   ```

3. **프로그램 실행**
   ```bash
   python stock.py
   ```

## 사용법
1. 프로그램 실행 후 홈 화면에서 '시뮬레이션 시작' 클릭.
2. 회사 목록에서 투자할 회사를 선택한 후 '매수' 또는 '매도' 버튼 클릭.
3. 포트폴리오 버튼을 클릭하여 보유 주식 및 손익 상태 확인.
4. 뉴스 및 경제 지표 확인하여 투자 전략 조정.
5. 목표 달성 여부를 확인하고 재시작 또는 종료 선택.

## 시스템 요구 사항
- 운영 체제: Windows, MacOS, Linux
- Python 3.8 이상
- pygame 라이브러리

## 개발 환경
- 언어: Python 3
- 라이브러리: pygame, random, sys, uuid, math, logging
- 개발도구: pycharm

## 라이선스
본 프로그램은 MIT 라이선스를 따릅니다.

## 문의
프로그램 관련 문의나 버그 리포트는 GitHub 이슈 또는 이메일을 통해 제출해 주세요.

