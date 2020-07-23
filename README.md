# MakeUpProject
게임 리소스[아바타 및 가상 인물] 생성 AI 프로젝트

## Description
- 게임 리소스 생성을 위한 AI기반 가상 얼굴 생성 및 Face Part Layer 추출

## Structure
- Based On Unity Project
- Open CV 
- dlib, Pillow
- Python3.6

## Install

## Build
- Android
- IoS
## Lisence

## Progress
- Unity 상에서의 FaceRecognition 구현, Face Part별 화장 기능 구현 예정 [20.07.10]
- Face LandMark 부위별 추출 완료 [20.07.13]
- 시장성 문제로 인한 프로젝트 잠정 중단[20.07.14]
- 프로젝트 내용 변경 : AI 기반 가상 얼굴 생성, 게임 리소스 활용을 위한 가상얼굴 추출 및 Face Layer[mouse eyebrow eye ...]를 추출[20.07.20]
- Face Layer, Cheek Layer, eyebrow Layer추출 구현[20.07.21]
- 섀도우, 눈 레이어 추가, 눈썹 레이어 수정[20.07.21]
- CartoonGAN 적용, 실사 사진 일러스트화적용 [20.07.23]

#### CartoonGAN processing 전/후
 <img src= "./Resources/21.jpg" width="212px"> <img src= "./Resources/20.jpg" width="212px">

#### FaceLayer Extraction
 <img src= "./Resources/3.PNG" width="400px"> <img src= "./Resources/4.png" width="212px">

#### Cheek Layer Extraction
 <img src= "./Resources/5.PNG" width="212px"> <img src= "./Resources/CheekLayer.png" width="310px">

#### Eyebrow Layer Extraction
 <img src= "./Resources/sample.png" width="212px"> <img src= "./Resources/eyebrow.png" width="212px">


## Revision History
- Initialize Project [20.07.11]
- Modified : Face Part LandMark Extraction  [20.07.13]
- Added : Face Layer Extraction Module [20.07.20]
- Added : Eyebrow, Cheek Layer Extraction Module [20.07.21]
- Modified : Shadow and Eye Layer, Modification Eyebrow Layer [20.07.22]