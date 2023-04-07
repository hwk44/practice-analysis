# practice-analysis
> 회귀, 분류, 시계열을 파이썬과 R을 사용해서 연습해 본 저장소 입니다.
<br/>
# 개발에 필요한 기초 지식
0. 해당 데이터는 메모리에 존재해야한다.


## 설정
* Python <= `3.10.10`
* `numpy`, `pandas`, `matplotlib`는 필수적으로 설치해주세요
* ipynb 를 위해서 `JupyterLab` 도 함께 설치해주세요.

```shell
$ python -m venv venv
$ .\venv\Scripts\activate
$ (venv) pip install -r requirements.txt
```

# 2023.04.06
## 프로젝트 시작시 주의사항
1. 폴더를 만드세요(한글x)
2. 파이썬을 사용해서 환경을 "격리"하세요
 -> `python -m venv venv`
3. 격리환경 사용
 -> .\venv\Scripts\activate
4. (venv) `pip install  numpy pandas seaborn jupyterlab`
5. (venv) `jupyter-lab`

### python -m venv venv 오류 발생시
 1. virtualenv 라이브러리 설치
 -> python -m pip install virtualenv
 2. 가상환경 생성
 -> python -m virtualenv venv
 -> (venv) venv\Scripts\activate

## 매개변수
1. 위치
2. 디폴트 매개변수
3. 이름

## 데이터 분석 
1. 데이터분석 => pandas => 데이터 전처리
2. 머신러닝 => 싸이킷런 => 회귀/분류
3. 딥러닝 => TF => 회귀/분류

## ToDo
- [ ] 회귀 문제(캘리포니아 집 값 데이터)
- [ ] 분류 문제(타이타닉 생존자 예측 , kaggle)
- [ ] 시계열 문제(문제 탐색 중)

