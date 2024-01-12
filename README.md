# System

1. 약속의 설계가 중요하다. 다른 시스템과 상호작용 할 때 버그가 발생하지 않고 잘 맞물려야한다.
2. 약속에는 경중이 존재한다. 하위약속은 상위약속에 어긋나면 안된다.

----------------------------------------------------------------------------------------------------------------------------------

시스템 제목 (System Title) : 운빨 업그레이드

시스템 슬로건 (System Slogan): 운이 좋으면 강해진다.

시스템 요소 (System Factor) : 
1. 업그레이드 자원
  A. 1회성 자원 : 업그레이드를 시도할 때 성공 유무에 관계없이 소모된다. 드랍 확률이 높다.
  B. 특별 자원 : 1회성 자원으로 업그레이드 되는 요소 외의 업그레이드 요소에 관여한다. 드랍 확률이 매우 낮다.
  C. 몬스터를 잡을 때 일정 확률로 드랍된다.

2. 업그레이드 요소
  A. 1회성 자원으로 업그레이드 되는 요소들은 업그레이드가 되기 위한 확률을 가지고 있다.
  B. 업그레이드 수치가 높아질수록 요구되는 1회성 자원량이 증가한다.
  C. 특별 자원으로 업그레이드 되는 요소들은 업그레이드 확률이 100%다.
  D. 특별 자원으로 업그레이드 되는 요소들은 업그레이드 수치에 상관 없이 요구되는 자원량이 동일하다.
  E. 1회성 자원으로 업그레이드 되는 요소들
    a. 공격력 증가
    b. 방어력 증가
    c. 최대 체력 증가
    d. 최대 기력 증가
  F. 특별 자원으로 업그레이드 되는 요소들
    a. 자동 공격 :               n초마다 범위 내에 적 n 명에게 플레이어의 공격과는 별개로 공격이 나간다.
    b. 1회성 자원 획득량 증가 :   1회성 자원 획득량이 n% 증가한다.
    c. 출현 적 증가 :            라운드마다 출현하는 적이 n마리 증가한다.

3. 소모품
  A. 몬스터를 잡을 때 일정 확률로 드랍된다. 드랍 확률이 매우 낮다.
  B. 1회성이며 플레이어에게 이로운 효과를 제공한다.
  C. 소모품들
    a. HP 증가 : 현재 체력을 n만큼 증가시킨다. 단, 최대 체력을 넘을수 없다.
    b. MP 증가 : 현재 기력을 n만큼 증가시킨다. 단, 최대 기력을 넘을수 없다.

4. 몬스터
  A. 라운드마다 등장하는 몬스터는 랜덤이다.
  B. 10라운드 다음 라운드는 보스다.
  C. 각각의 몬스터는 스텟 수치들이 다르다. 아래의 특징들을 조합하여 각각의 몬스터마다 특징을 가지게 한다.
    a. 공격 속도
    b. 데미지
    c. 방어력
    d. 이동 속도
    e. 원거리 공격 유무
    f. 체력
  D. 라운드가 높아짐에 따라 몬스터의 스텟 수치는 증가한다.
  E. 최초 라운드마다 등장하는 몬스터의 수는 20마리이며 n마리씩 텀을 두고 나온다.
  F. 보스는 10라운드까지 나오는 몬스터들에 비해 스텟 수치가 매우 높으며 업그레이드가 충분하지 않으면 잡기 매우 힘들다.
