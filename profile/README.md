# Agentic AI기술팀
Agentic AI기술팀 을 위한 GitHub Organization 입니다.
  

## 📝Repository Naming Convention
모든 리포지토리 이름은 다음 규칙에 따라 생성 바랍니다.
- 영문 소문자 (a–z) 만 사용
- 단어 구분은 하이픈(-) 으로 연결
- 숫자 사용 가능 (필요한 경우)
- 공백, 밑줄(_), 대문자, 특수문자 사용 금지

✅ 예시
- refinery-docs
- cpo-trainer-peft
- eval-slurm

❌ 잘못된 예시
- Model-Refinery (대문자 사용)
- model refinery (공백 사용)


## 🏷 Repository Topic Tagging Rule
아래 표에 따라 각 레포지토리에 적합한 Topic 을 부여바랍니다.
- 각 구분에서 해당하는 Topic 을 최소 1개 이상 부여합니다.
- 아래 표에 표기되어있는 Topic 들 중 적합한 것이 없다면 자체적으로 부여해도 괜찮습니다.
- 모든 Topic 은 **소문자** 와 **하이픈(-)** 을 사용합니다.

| 구분       | 태그 예시                       | 설명 |
|------------|----------------------------------|------|
| 🏢 파트 영역 | `refiner`, `finetuning`, `evaluation`, `router` | 레포지토리 작업 Owner 파트 |
| 📌 목적 구분 | `product`, `asset`, `doc` | 해당 레포지토리의 성격 |

Topic Tag 적용 방법 : `적용할 레포지토리` > `About ⚙` > `Topics` 에 추가


## 👥 팀 구성원 Username


|No.|이름   |Username           |비고  |
|---|------|-------------------|----|
|1  |정윤정	|myde arlutein      ||
|-	|김영민	|aoamore            |~1/23|
|2	|박선진	|narfian            ||
|3	|임승영	|seungyounglim      ||
|4	|김종완	|matia0521          ||
|5	|김지아	|kja815             ||
|6	|윤성종	|sean-yoon          ||
|7	|전창원	|changwonjeon       ||
|8	|강민수	|minsookang38       ||
|9	|김민정	|Minjung25          ||
|10	|김석환	|KSH94              ||
|11	|김영운	|ywkim92            ||
|12	|박동재	|PARKDONGJAE        ||
|13	|배노협	|hyeobiiii          ||
|-	|유선아	|seona21            |~1/23|
|14	|이민형	|inoutro            ||
|15	|이석진	|iwill231           ||
|16	|이주호	|juho1107           ||
|17	|이지혜	|modesta-jihye-lee  ||
|18	|장하림	|hrjang9004         ||
|-	|최성우	|swchoi1994         |~1/23|
|19	|정한솔	|hanssoljung        ||
|20	|주민재	|minjaeju           ||
|21	|강연호	|octokang           ||
|22	|유창민	|fluentmin          ||
|23	|이연서	|reneovolee         ||
|-	|조은기	|gumgizoa           |~1/23|

## 👥 팀 외 구성원 (Outside Collaborators)

|이름  |직급/직책  |Username          | 기간   |  관련 작업 |
|------|-----------|------------------|--------|--------|
|김다인 |선임       |dain5832          |11/10 - 12/31| 라우터 관련 Repo 공동 개발 |
|김대훈 |선임       |daehun614         |11/25 - 12/31| refiner-trainer 에 Agentic AI Lab 에셋 탑재 |



## 그 외 유용한 정보들

### git 자격증명 cache
GitHub 은 인증을 PAT (Personal Access Token) 로 하다보니 매번 토큰값을 복붙하는게 힘들다면, 캐싱 하는 것을 추천 (timeout 초단위)
```bash
git config --global credential.helper 'cache --timeout=31536000'
```
