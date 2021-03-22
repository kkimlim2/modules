# 목차

1. KNN
2. DBSCAN
3. Local Outlier Factor(LOF)
4. Isolation Forest
5. One class support vector machine(SVM)



# 1. KNN

- 장: 
- 단: 거리기반(시간) 

- 활용방안: 결측치 대체
- 고려사항: 범주형 변수의 대체(어떤 class가 있는 경우 가능하지만, 그렇지 않고 모두가 다른(예를 들어 이름)의 경우는 불가능함)          
          :  data scaling 

# 2. DBSCAN

- 장: 높은 활용도, 기하학적 군집화
- 단: 거리기반(시간), 파라미터 탐색(이에 대한 대체방안으로 HDBSCAN, 그러나 여전히 입실론은 사용자가 설정해야 함)

- 활용방안: (군집화를 통한) 결측치 대체, 이상치 탐색
- 고려사항: 결측치가 있는 열은 어떻게 군집화 할것인가? 

# 3. LOF

- 장: global한 아웃라이어만 찾는 여타 방식과 달리, local한 아웃라이어 탐색 가능
- 단: (시간), 파라미터 탐색

- 활용방안: 이상치 탐색

# 4. Iforest (+ extended iforest) 

- 장: 짧은 시간
- 단: 파라미터 탐색(contamination rate 설정값에 결과값이 변동)

- 활용방안: 이상치 탐색

# 5. One class support vector machine(SVM) 

- 장:
- 단: outlier를 탐색하기 위해서 그 전에 inlier만 있는 셋이 필요함

- 활용방안: 이상치 탐색(inlier 셋이 있다는 가정 하<-지켜지기 어려움)





