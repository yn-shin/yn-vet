---
share: "true"
---

# Computed Tomography (컴퓨터 단층 촬영)

- Tmography : slice/section + to describe
- X-ray의 3차원 버전

- 마취해야 하는 단점 / 가장 정밀도 높음
- 응급 상황에서는, 환자 움직임이 크지 않다면, 그냥 케이지채로 찍기도 함

### Basics

- Slice thickness 
	- Thin slice : 얇게 자르면 → 퀄리티가 높아지지만 데이터 양이 많아짐
	- Thick slice : 두껍게 자르면 → 러프하게 찍음, scan time이 짧고 데이터 양이 적음
- Slice interval : 간격
	- interval 짧을수록 많은 ㅇㅁㅈ, 세세하게

### Components & Terminology

- Gantry : X-ray 방출
- Console : 공간 구분되어 있음
- Patient table : 환자 눕는 곳
- Injector : 조영제를 주사하는 기계

- Multi-detector CT (MDCT) 
	- Slice : 한 번의 회전으로 얻을 수 있는 단면 이미지의 수
	- Channel : detector가 수집하는 데이터 라인의 수
	- 의 숫자가 높을수록 해상도가 높고, 스캔 타임 빨라지고, 방사선 피폭 감소, motion artifact 감소

|                       |                                                                                                                                         |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Attenuation (감쇠)      | Hypoattenuated ↔ Hyperattenuated                                                                                                        |
| Housefield unit(HU)   | - Air : -1000 감쇠도 (매우 까맣게)<br>- Fat : -100<br>- Water : 0<br>- 조영제 : 100-500                                                            |
| Window                | Window : 원하는 장기의 감쇠도에 맞게 더 자세히 들여다볼 수 있음<br>: lung, bone, soft tissue windows, etc                                                      |
| Plane                 | - Transverse, axial / Dorsal, coronal / Sagittal / Multiplanar reconstruction(MPR)<br>- MRI는 단면마다 다 따로 찍어야 함                            |
| Volume rendering (VR) | 3D로 구현하는 기능 <br>: 해부학적 구조를 직관적으로 보고, 수술 플랜 세우기에 용이, medical teaching에 유용<br>- occipital bone, C1, C2의 3D 구현<br>- CVC, PV 등 혈관 구조의 3D 구현 |

### Contrast medium

- 비요오드성 조영제 보통 사용
- kg당 2-3mL 
- 혈관을 통해 조영제를 넣어, 간질에 뻗어나가는 양상에 따라 다르게 나타남
- Side effect : 신장 기능의 악화; 신부전 환자에선 주의

### Procedure

- Pre-anesthesia
- Intubation
- **Positioning** : 판독을 잘하려면 positioning 잘 되어야
- Pre-contrast scan
- Contrast enhancement
- Post-contrast scan
- Recovery
- Reconstruction

### CT를 찍는 이유?

- Anatomy (normal VS abnormal)
- Cancer origin : 종양의 유래를 판단할 때
- Metastasis (e.g., regional lymph node, lung, distant metastasis, etc) : 종양이 어느 정도로 전이되었는지
- Cancer staging (size, metastasis, prognosis) 
- Emergency (e.g., acute hemorrhage) : 응급 상황에서도 매우 유용
- Treatment planning (e.g., lymphoma vs other neoplasia)
- Surgery planning (e.g., feeding artery) : 

### Other technique

- Triple phase : 조영 전 / 동맥기 / 문맥기 / 지연기 구분해서 촬영
- CT guided biopsy : 비강종양 등은 주변에 염증 ↑ - 종양의 core를 biopsy해서 진단 정확도를 높일 수 있음
- Lymphangiography : 림프관 조영, 림프액이 관을 타고 올라가는 과정
- Perfusion : 혈류가 얼마나 들어가는지 - infarction 등을 판단

# 2. MRI (Magnetic resonance imaging)

- 자석에서 비롯되는 자기력을 이용하여 공명을 일으키고 영상으로 변환
- 강력한 자기장을 만들어서 몸 안의 수소 원자들을 한 방향으로 정렬 → 라디오파를 쏴서 수소들을 흔들어 놓고, 그 수소들이 제자리로 돌아가면서 방출하는 에너지를 감지
- 구성 : 마취기, 수액 펌프, 모니터, 조영제 주입기

- Tesla = strength of magnetic field. 
- 0.5T, 1.5T, 3T.. 지구의 자기장이 2000gauss. MRI는 매우 강한 자기장을 일으킨다.

| 장점                                                                                                  | 단점                                                                                                      |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| - 방사선 노출이 없음<br>- 연부조직 해상도가 우수<br>- 다양한 조직 대비 강조 영상 생성<br>- 다각도 영상 가능<br>- 조영제의 부작용 적음 (gadolinium) | - very expensive<br>- 마취 시간이 길다<br>-  motion artifact<br>- 금속 성분이 있으면 위험/quality 저하<br>(아니면 그게 망가지거나..) |

|           |                                                                                      |
| --------- | ------------------------------------------------------------------------------------ |
| **T1**    | 해부학적 구조, 위치를 파악하기 좋음. <br>**물은 어둡게, 지방은 밝게**                                         |
| **T2**    | 가장 많이 사용. 대부분의 병변이 밝게(고신호로) 보인다.<br>**물(뇌척수액)은 밝게, 지방도 밝게**                          |
| **FLAIR** | T2 영상에서 하얗게 보이는 CSF 신호를 억제.<br>**뇌척수액은 어둡게, 병변은 밝게** ⇒ 뇌척수액과 병변 감별                   |
| **STIR**  | 지방은 T1, T2에서 둘 다 밝게 보임 → T1 영상에서 지방 신호를 억제.<br>**지방이 어둡게** ⇒ 지방이 많은 부위에서 병변 대비도를 높임. |
| **DWI**   | **물의 확산이 제한된 부위가 밝게 보임.** ⇒ 급성 경색을 확인.                                               |
|           | ![[Pasted image 20250611114928.png\|350]]                                            |

### Contrast media

- T1 신호 증강, 병변을 밝게 보이게 함.
- 염증, 부종 등으로 혈관 투과성이 증가할 때 조영 효과 발생.

### Indication disease

- 뇌, 신경계 부위에 가장 ↑ 

>[!check] Indication disease
>- Brain
>	- Meningoencephalitis (MUE, GME, NME) 
>	- Hydrocephalus 
>	- Chiari-like malformation syndrome 
>	- Caudal occipital malformation syndrome (COMS) 
>	- Brain tumors (meningioma, glioma, etc.) 
>	- Brain infarction, hemorrhage 
>	- Cognitive dysfunction syndrome (CDS)
>- Spinal cord
>	- IVDD (protrusion, extrusion) 
>	- Spinal cord tumor
>	- AAI 
>	- Vertebral fracture
>	- Myelitis

# 3. Veterinary Interventional Radiology

- 최소침습적 시술을 통해 치료

### 

- C-arm / Fluoroscopy : real-time radiographic image : 실시간으로 심장이 뛰는 것까지 & 원하는 방향으로 돌려가면서 
- DSA : 혈관만 조영하는 기법
- 이렇게 길을 확인 = **Road mapping** ⇒ guide wire 등 더 쉬움

### Equipment

|                             |                                                             |
| --------------------------- | ----------------------------------------------------------- |
| Access needles/catheter     | - "점"을 만드는 과정 : 최소침습 필요<br>- 카테터 많이 사용 (21/22G, 18G)        |
| Guide wires                 | - needle의 2배는 되어야 함<br>- wire의 끝부분 모양이 다 다름 : 필요에 따라 선택     |
| Angiographic catheters : 본체 | - 조영제 투여, 등을 다 이걸로 함<br>- French 라는 단위를 씀 <br>- Tip 모양 다 다름 |
| Sheaths & Dilators          | - sheath : <br>- dilator : 확장시키는 용도                         |

- 구멍을 뚫고 가이드 와이어 먼저 → 그래야 카테터 들어감
- Balloon catheters : 필요에 따라 부풀려서 협착부를 해소시킬 수 있음
- Embolization materials : 색전증

### Vascular access

- Arterial access : common carotid artery & femoral artery
- Venous access : jugular vein & femoral vein

| Modified Seldinger's technique            |                                                                      |
| ----------------------------------------- | -------------------------------------------------------------------- |
| ![[Pasted image 20250611121935.png\|300]] | 1. needle로 혈관을 뚫는다<br>2. 가이드 와이어 장착<br>3. Sheath(통로)&dilator를 같이 넣어줌 |

### Interventional oncology

|                                                |                                                                                                                                                                                 |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Palliative stenting for malignant obstructions | - 환자의 삶의 질 개선 (pylorus가 막혔거나, colon이 막혔거나,                                                                                                                                      |
| Intra-arterial chemotherapy                    | - 방광에 생긴 종양 → 방광 혈류에 항암제 공급<br>- 정확한 부위만 target 해서 줄 수 있음, 전신 공급보다 훨씬  ↑                                                                                                        |
| Trans-arterial chemoembolization (TACE)        | - 수술로 해결 못 하는 경우 가능한 치료 옵션<br>- 원하는 곳에 색전 (혈류 공급 차단)<br>- non-target embolization도 생길 수 있음<br>- 간종양을 줄여줄 수 있는 방법<br>- DEB-TACE : 구슬을 삽입, 구슬에서 지속적으로 항암제 분출 (drug-eluting beads) |

# 3. Radiotherapy (RT)

- 고선량의 방사선을 종양세포에 조사해서 종양을 control
- 암치료의 3대 요법으로 꼽힘 (수술치료, 항암치료, 방사선 치료 + 최소침습)

### 원리

- 직접 작용 : DNA 이중나선 구조 파괴
- 간접 작용 : 세포내 물 분자에 작용해 free radical 등 생성 → 이차적 DNA 손상 유발
- 분할 조사 : 4R을 활용해 정상 세포는 보호, 암세포는 약화
	- **Repair** : 손상된 DNA를 세포가 복구하는 능력 ⇒ 정상 세포를 보호하기 유리
	- **Repopulation** : 생존 세포들이 다시 증식 ⇒ 분할 조사로 여러 번 쏴서 억제
	- **Reassortment** (Redistribution) : 세포 주기에 따라 달라지는 방사선 민감도
	- **Reoxygenation** : hypoxic한 종양세포가 먼저 사멸 ⇒ 저산소 세포가 다시 자라나면, 분할조사로 여러번 때림

### 장점

- 보호자 및 수의사에게 미치는 영향 
	- 바깥 사람에게 피폭X
	- 항암 후에 만지면 안되고.. 그런데, 이건 방사선이 남아있지 않음
- 종양 부위에 집중 → 전신 부작용 ↓ 
- 완치는 어려워도 삶의 질 개선
- 대부분 통원 치료 가능
- 무색, 무취, 무미, 무통

### 치료실

- 차폐를 위해 벽이 1m 이상 되어야 함
- 방사선 치료기가 돌아가면서 방사선을 쏘며 치료

### 용어

- Gray (Gy): 흡수선량 (unit of radiation)
	- 1kg 의 질량에 1J 의 에너지가 전달되는 값
	- ex. 10Gy > 8Gy > 4Gy ...
- Fraction (Fr) : 치료 횟수 
	- ex. 10 Fr = 10번에 걸쳐서 치료
- Prescription dose : 처방선량, total dose 
	- Total dose = m (Gy) x n (Fr) 
	- ex. 24 Gy (total dose) = 8 Gy x 3 F

|                                                                                  |                                                                                                                  |
| -------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| ![[Pasted image 20250611124318.png\|300]]<br>종양 세포 방사선량은 늘리고, OAR 선량은 최대한 줄여야 함. | - GTV (gross tumor volume)<br>- CTV (clinical tumor volume)<br>- PTV (planning tumor volume<br>⇒ GTV < CTV < PTV |
|                                                                                  | - OAR<br>: Eye, Lens, Optic nerve, optic chiasm, Brain, Spinal cord, Esophageous,                                |
