# Machine-Learning-Sidewalk-damage
2024 종합설계 : 휠체어 사용자를 위한 보도파손 경고 어플리케이션의 머신러닝 학습 부분입니다.

안드로이드 및 메인 코드는 이쪽입니다. [https://github.com/j0gea/Warning-App-of-sidewalk-damage](https://github.com/j0gea/Warning-App-of-sidewalk-damage)

## 2024 07 29 up
- wandb 추가
- 파손 데이터만 따로 옮기는 코드 추가
- 텐서플로루 라이트 변환 코드 추

## 2024 07 23 up
[https://colab.research.google.com/drive/1J_ygo7RvOVmFl0snr8exQfpeqdqDLtIh?usp=sharing](https://colab.research.google.com/drive/1J_ygo7RvOVmFl0snr8exQfpeqdqDLtIh?usp=sharing)
- JSON -> YOLOv5 형식 txt 변환 코드
- 한 집단의 파일 train / val 변환 코드
- yaml 파일 생성 코드 

- 버그 수정 (JSON -> txt)

---
## 필요한 업데이트 사항
1. 이미지 사이즈 줄여서 학습시키는게 가능할지( --img 416 가 실제로 적용되는지에 대한 여부)
2. 가중치 이어받아서 학습할 수 있게
3. 다른 데이터셋도 적용
4. 이미지 박스 성능 높이기(혹은 JSON 박스 그대로 사용 가능한지)
