# SMFC

<h1 align="center"> 👼Safe map for Children 👶</h1>
<p>
  <img src="https://img.shields.io/badge/version-0.0.1-gray.svg" />
  <img src="https://img.shields.io/badge/flask-1.0.2-blue.svg" />
  <img src="https://img.shields.io/badge/template-jinja2-blue.svg" />
  <a href="https://github.com/kyujonglee/Project-SMFC-/README.md#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-none-red.svg" target="_blank" />
  </a>
  <img alt="Maintenance" src="https://img.shields.io/badge/Maintained-nope-green.svg" target="_blank" />
</p>

## 프로젝트 목표
 - 2018년 8월 기준 어린이 안전에 관한 이슈가 많았었음. 따라서 어린이에게 안전지킴이집,경찰서,CCTV 등을 미리 알려주어 위험에 노출되는 상황을 비교적 줄이며, 위험에 노출됐을 시 도움을 어디에 요청해야 하는지 알려줌으로써 어린이가 안전할 수 있도록 함. 이것은 어린이가 위험에 노출되는 것을 근본적으로 제거한 것이 아니지만, 대비할 수 있다는 것에 의의가 있음.
 
## 사용한 기술
 - Flask(웹 페이지 구현), selenium(크롤링), python의 pandas 라이브러리(데이터 전처리), Tmap, daum 지도, sklearn, html, css, javascript

[![Main](/image/소개.png)](메인페이지)
[![Main](/image/소개2.png)](메인페이지)
[![Main](/image/지도캡처1(위험).png)](메인페이지)

`경찰서, 학교, CCTV 의 위치를 지도에 나타내줌.
각각의 수를 볼 수 있으며, 머신러닝 모델을 통해 그 지역의 안전, 위험, 보통도 볼 수 있음.
왼쪽 사이드바를 통해 원하는 장소만 볼 수 있음.`

[![Main](/image/도움말.png)](메인페이지)

`사용자의 편의를 위해 도움말 기능 제공`

[![Main](/image/데이터분석.png)](메인페이지)
[![Main](/image/데이터분석2.png)](메인페이지)
[![Main](/image/데이터분석3.png)](메인페이지)
[![Main](/image/데이터분석4.png)](메인페이지)
[![Main](/image/데이터분석5.png)](메인페이지)


## 소감
```
빅데이터를 다뤄서 web 을 만드는 첫번째 프로젝트였다. 프로젝트를 진행하면서 공공데이터를 
이용했습니다.  
공공데이터가 잘못된 입력된 데이터, 값이 없는 데이터 등이 많아서 데이터 전처리에 예상보다 많은 시간이 소요되었습니다. 
실제로 많은 데이터를 다뤄 web을 만들어본 좋은 경험이었습니다. 
여러 데이터를 한번에 불러오기 때문에 사이트가 느려지는 현상이 있었지만, 쓰레드를 이용하여 해결하였습니다.
여러 머신러닝 모델들을 돌려보면서 실제로는 데이터가 지저분하고, 원하는 결과가 나오기 힘들다는 것을 깨달았습니다.
```
***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
