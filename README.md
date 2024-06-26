# WasteWise
EST해커톤

|MVP|고도화|
|---|---|
|![image](https://github.com/EST-hackathon-6-Team/WasteWise/assets/99312529/1ad1ba68-1138-4c4c-9ebc-00dd8f917d8c)|![image](https://github.com/EST-hackathon-6-Team/WasteWise/assets/99312529/62d4f412-15a5-4092-adf0-3530ab958898)|
||- **SpringBoot**: 복잡한 비즈니스 로직, 데이터베이스 연동, 트랜잭션 관리 등 전통적인 엔터프라이즈 애플리케이션에 적합한 작업을 처리<br>- **FastAPI**: 빠른 응답, 비동기 처리가 필요한 작업, 머신 러닝 모델 서빙<br><br>- SpringBoot와 FastAPI는 gRPC로 통신<br>|


https://github.com/EST-hackathon-6-Team/WasteWise/assets/99312529/ecd17d4a-78cf-42f0-936b-a8b6cffdcc6f

|||
|---|---|
|![image](https://github.com/EST-hackathon-6-Team/WasteWise/assets/99312529/fd0aec7b-7797-4ba7-8246-4e44904028b0)|![image](https://github.com/EST-hackathon-6-Team/WasteWise/assets/99312529/9a7e25b5-ad4c-4ef6-a0ef-2171a0daf08c)|

## 성과: 우수상 

<img src="https://github.com/EST-hackathon-6-Team/WasteWise/assets/99312529/7273d83f-859a-4864-8ec4-7d58592e4c4f" width="500">


## 멤버
<table style="width: 100%;">
<tr>
    <td align="center"><b>조은수</b></td>
    <td align="center"><b>김민지</b></td>
</tr>
<tr> 
    <td align="center">기획</td>
    <td align="center">기획</td>
</tr> 
<tr> 
    <td align="center"></td>
    <td align="center"</td>
</tr> 
</table>
<table style="width: 100%;">
<tr>
    <td align="center"><b>한재현</b></td>
    <td align="center"><b>이승후</b></td>
    <td align="center"><b>백승진</b></td>
</tr>
<tr> 
    <td align="center">AI개발</td>
    <td align="center">AI개발</td>
    <td align="center">Backend, Front</td>
</tr> 
<tr> 
    <td align="center"></td>
    <td align="center"</td>
    <td align="center"></td>
</tr> 
</table>

## 피드백

### 양서연님

발표

- 발표 스킬이 좋습니다.
- 디자인, 발표자료 구성 좋습니다.

기획

- 자취 시, 제일 어려운 것이 재활용인만큼 써보고 싶은 서비스입니다.
- 유용하고 실질적으로 필요한 서비스이기 때문에, 조금더 리서치하면 비슷한 서비스를 많이 확인할 수 있어서 그 차별성을 고민하는 것이 중요한데, 잘하셨다. 조금 더 찾아봐도 좋을 듯
    - 한국 쓰레기 배출 규정까지 고민한 서비스는 아직 많이 없을 거다. 차별성 잘 찾았습니다.

AI 개발

- GPT 4.0 비젼모델까지 가능한 것을 사용하려고 한 노력이 좋았다.
- LangChain과 LAG 추가 활용하려고 한 노력도 좋게 봤습니다.
- 이미지분류(chatGPT4.0)와 LLM(chatGPT) 구분하여 적어둔 이유는?
    - 이유 : 특별한 이유가 있기보다, 나중에 구분하기 위해
        
        이미지모델 고도화하는 목표가 있기 때문에 분류했다.
        
    - 이미지 분류 모델을 따로 쓰고, 쓰레기 인식 모델을 따로 개발하여 특화시킨다면, 아마 정확도가 많이 올라갈 것이며, 그걸 고려했다는 점 굉장히 칭찬합니다.
- TIP!
    - 이미지를 분류(classification)하는 것과 설명(detection)하는 것은 조금 다르다 → 정확하지만 이미지의 특성에 영향을 많이 받음(조도, 빛, 반사, 색상 등) 오차 가능성있음
    - CHAtGPT는 멀티모달모델 : 이미지에대한 설명을 할 수 있고, 제너럴라이즈하는 경향이 있음 → 감지정확도가 높다고 해서 결과가 좋지 않을 수도 있음
    - 로보스트(robust)하게 분류할 수 있다.
- LangChain과 LAG를 사용했다는 것 자체가 좋은 시도다.
    - 지자체별 정보를 crowling해서 document를 만들어서 searching을 하는 건가?
    - 답변 : 이미지와 pdf crowling에 대한 어려움이 있었다.
- 랭체인을 사용할 줄 알았기 때문에, 답변양식에 맞게 답이 나올 수 있도록 한다던지, 가이드에 따라 답변이 나온다던지 등이 시도가 좋다,
- 파인튜닝이 아닌, document를 기반으로 템플릿으로 LangChain을 엮어 파인튜닝한 것 처럼 보이는 방법도 많이 있다.
    - 파인튜닝보다 리소스가 덜 들긴 하지만, 단점은 벡터를 긁어서 레퍼런스를 요청하기 때문에, 요청하는 토큰 수의 비용이 증가하는 상황이 생김
    - 파인튜닝 방식 혹은 LangChain, RAG : 둘 중 어떤 방법이 좋은지는 실험하고, 정확도 비교하면 좋을 것 같다.

### 김충환님

기획(문제정의)

- 우리나라가 전세계에서 재활용 압도적 1위
- 서비스의 목표가 명확했으면 좋겠습니다.
    - 물질 재활용율을 높이는 것이 목적인지? 현실적으로 높일 수 있는건지?
    - 햇반 등 현실적 문제→분류시간을 줄이는 것인지?! (개인적으로 분류시간이 축소될 수 있을 거라고 생각함)
    - 문제의 공감대형성은 양호했으나,
    - 실생활에서는 가이드를 몰라서보다는 실천을 안하는 것이 문제라고 업계에서 알고 있다?!
        - 페트병과 비닐을 분리하는 것, 용기를 씻어내서 분리수거하는 것
- 쓰레기별 세부사진 학습이 어렵다고 얘기했는데, 제일 관건이다.
- 그 분류를 통해 상세적인 가이드를 주는 것이 중요할텐데 이것에 대한 대안제시가 잘 안되어있다고 생각함
    - 쓰레기가 오염이 됐다, 낙서가 됐다. 오염이 됐다 등
    - 추가 조치가 필요하거나 재활용 자체가 안되는 것을 안내하는 것 현실적 대안이기 때문에 로드맵에서도 잘 녹였으면 좋겠습니다.
        - 사전 서비스 지역에서 어떤 효과(명확한 목표에 따른)가 있었는지 설명하면 자연스럽게 서비스 고도화가 된다고 생각
        - 검증지표(분류시간 감소 등)가 리즈너블(reasonable)해야지 서비스로 더 가치가 있을 거라고 판단됨

### 조성연님

발표

- 문제제기-퀴즈-해결 등 발표 흐름이 굉장히 좋았다.
    - 문제에서 틀려서 → 더집중하게 되었던 효과가 있었음
    

백엔드 아키텍쳐 구조

- 현재와 앞으로의 방안을 함께 도식화해줘서 좋았다. 설명 부탁드린다.
    - 답변 :  MVP는 springboot랑 fastAPI를 함께 사용함
        - 이유 : 백엔드 개발자와 AI개발자의 기술 스택이 달라서 그 중에서 프레임워크를 선택해서 각 기능별로 나누어 병렬적으로 처리하면 어떨까라는 생각에서 고도화방안을 설계함.
        - 프레임워크도 마찬가지로 백엔드개발자로서 html css js만 구현했는데 특정기능 구현에는 한계가 있어서 프론트엔드에도  도입하고자함
        - 코드 자동화 CICD도 도입하고,
        - AWS에 reKognition이라고 있는데, 기술 스택 선택에 앞서서 이미지 분석에 있어서 물체 감지, 얼굴인식 등 이미지분석이 가능한 이미지 분석 AWS기능을 사용할 수 있어서 사용하면 어떨까
        - 현재는 GPT응답으로 쓰레기 분리를 응답받고 있지만, 비용적, 기술적 측면 고려해서 추후 도입할지 알아보려고 합니다.
    - 답변 매우 잘 들었고, 아키텍처를 보면서 유추를 했는데 그대로 답변을 해주셔서 좋았다.

사용자 측면

- 사용법이 매우 간편하여, UX측면에서도 사용성이 좋아보여서 좋았다
- 비슷한 서비스에 대한 차별점이 있었으면 좋겠다!
- MVP에서는 구현내용을 충분히 잘 구현한 것 같아서 좋게 봤습니다.


## 현재 개발 중단
사유: 
- 아이디어 변경 예정 (더 신박하고 경쟁력있는 아이디어로!)
- 협업 방식 변경


## kdt 해커톤 수상을 목표로!!

## 개인적인 후기

'다시는 해커톤을 하지 말아야지' 생각했지만 이보다 단기간 실력향상이 빠른 방법은 없는것 같다. 
해커톤 동안 많이 배웠고 무엇이 부족했는지, 무엇을 공부해야하는지 알게 되었다. 다음 해커톤도 참여해야지!


1. 배운점
- FastAPI를 새롭게 배웠다.
- AWS S3를 사용하였다.
- 다른 직무를 가진 팀원과의 커뮤니케이션 능력

2. 아쉬운 점
- 타임 어택으로 인한 스트레스, 코드의 질 하락, 결과 불만족
