# 1. 서론

게임 개발 기술이 매우 빠르게 발달하는 요즘 시대에 제일 성공적으로 꼽히는 게임 장르 중 하나는 오픈월드(Open-World) 게임일 것이다. 본격적인 GOTY 집계가 시작된 2004년 이래로, 매년마다 집계된 역대 최다 GOTY 수상작 15 작품 중 무려 7 작품이 오픈월드 게임이다. 기간을 최근 4년으로 한정한다면, 4년 연속으로 오픈월드 게임이 최다 GOTY 수상작을 휩쓸었다. 게임 업계에 한 획을 그은 유명한 게임 시리즈인 <젤다의 전설>의 최신작인 <젤다의 전설: 야생의 숨결>[Nintendo EPD, 2017]의 경우 기존 작품보다 훨씬 더 오픈월드 게임으로서의 특징을 강화하였다. 그 결과 젤다의 전설은 1998년에 발매된 <젤다의 전설: 시간의 오카리나>[Nintendo EAD, 1998.] 이후로 처음으로 AIAS와 GDC 두 시상식에서 GOTY를 수상하며 2017년 역대 최고의 게임이라고 평가받았다. 오픈월드 장르를 메이저 시장으로 끌어올린 <GTA 시리즈>의 최신작인 <GTA V>[Rockstar North, 2013]는 기네스북에 24시간 내에 가장 많이 팔린 게임, 돈을 가장 많이 번 게임 등의 제목으로 총 7가지 항목에 등재될 정도로 선풍적인 인기를 끌었다. 또한 모든 인디 게임 업체의 꿈인 <Minecraft>[Mojang, 2011]라는 게임 또한 오픈월드 장르이며, 오픈월드 장르가 단순히 대기업만이 제작할 수 있는 장르가 아님을 보여주며, 가장 많이 팔린 인디 게임 등 총 12개의 항목으로 기네스북에 등재되기도 했다.
  
오픈월드 장르가 이렇듯 게임 산업의 주류로 자리 잡는 이 상황에서 다수의 오픈월드 게임이 제작되고, 출시되고 있다. 헌데 다수의 오픈월드 게임이 제작됨에 따라, 지난 작품에서는 진행되지 않았던 새로운 논의들, 또한 문제점들이 제기되고 있다. 그 중 하나가 바로 플레이어의 캐릭터 디자인에 관한 것이다. 오픈월드의 자유로운 특성답게, 플레이어의 캐릭터를 플레이어 자체에 투영시켜, 캐릭터의 행동, 생각 등 모든 것이 플레이어를 완벽하게 투영시킬 수 있게 캐릭터 자체엔 아무 의미가 없게 디자인해야하는 것인지, 아니면 캐릭터 자체에도 인격과 특성 등을 투여하여 플레이어의 생각과 다른 행동을 할 수 있게 만들어야하는지에 대한 논의가 활발하다. <Minecraft>의 경우 플레이어의 캐릭터는 곧 플레이어다. 캐릭터에겐 별도의 이름, 성격 등이 없으며, 모든 특성은 플레이어에 의해 결정된다. <GTA 시리즈>는 다르다. <GTA V>의 경우 무려 세 명의 캐릭터가 플레이어가 조종할 수 있는 캐릭터들인데, 각자 개성이 있고 성격이 존재한다. 즉, 플레이어를 캐릭터에 투영하는데 한계가 있다. 이러한 부분은 게임의 몰입성과 재미와 밀접하게 관련되어있기에, 오픈월드 게임을 디자인할 때 매우 중요하게 논의된다. 그렇기 때문에 이 논문에서는 게임 캐릭터를 디자인할 때 어떤 전략을 사용해야 효과적으로 “재미있는” 게임을 디자인할 수 있는지에 대해서 최근 몇 년간의 유명 오픈월드 게임들을 바탕으로 분석해보고자 한다.


# 2. 오픈월드 게임 분석
## 1. 오픈월드 게임의 정의

 오픈월드 게임이라는 장르는 RPG, FPS 등과 같이 구체적으로 정의할 수 있는 장르가 아니다. 오픈월드 게임의 정의는 구체적이지는 않지만, 일정한 특징들을 통해 구분할 수 있다. 오픈월드의 대표적인 특징은 바로 비선형성이다. 기존의 게임 방식은 닫힌 방식, 혹은 선형적인 방식으로 진행이 되었다. 게임에는 특정 규칙이 있고, 특징 목표가 있으며, 이 목표에 도달하려면 규칙에 따라 '순서'대로 무언가를 해야 한다. 보드게임을 떠올린다면 게임의 선형성이 어떤 의미인지 이해하기 쉽다. 오픈월드 게임은 이러한 닫힌 구조를 열음(open)으로써 비선형성을 띠게 되고, 이것이 오픈월드의 핵심이다. 허나 문제는 그 다음에 발생한다. 무엇을 "개방"해야 오픈월드라고 부를 수 있느냐는 질문이다. 이 질문에 답하기 위해서는 오픈월드 게임이라고 불렸거나, 토대가 된 게임들을 통해 오픈월드의 핵심적인 특징을 통시적으로 알아보도록 하자.
 
## 2. 오픈월드 게임의 특징

### 1. 공간의 개방성

오픈월드 장르를 논할 때 처음 등장하는 게임은 『울티마 I: The First Age of Darkness』[Richard Garriott·Origin Systems, 1981.]이다. <울티마> 시리즈는 초창기 RPG일 뿐만 아니라, "공간의 개방성"을 처음으로 선보인 게임이다. 공간의 개방성이란 플레이어가 상대적으로 거대한 게임 월드를 자유롭게 탐험할 수 있게 게임 월드의 제한을 줄인 것을 의미한다. 통상적인 게임들은 <슈퍼 마리오 브라더스>[Nintendo Creative Department, 1985.]같이 플레이어 캐릭터의 움직임의 진행 방향을 제한하거나, <팩맨>[Namco 1980.]와 같이 게임의 맵이 플레이하는 기기의 모니터보다 작아 플레이어의 움직임이 자유롭다 하더라도 공간 자체에서는 벗어나지 못하게 막아놓아 게임의 선형성을 강조했다. 물론 <메트로이드>[Nintendo R&D1 1986.]와 같은 게임에서는 <슈퍼 마리오 브라더스>와 같이 한쪽으로 밖에 진행할 수 없는 대부분의 사이드 스크롤 게임과는 달리 양 옆으로 진행할 수 있으나, 실질적으로 의미가 있는 방향은 정해져있기 때문에 공간은 여전히 폐쇄적이라고 볼 수 있다. 이에 반해 울티마 1은 늪지대, 바다, 언덕과 같은 다양한 지형을 포함하고 당시 기술적 한계에 도전하는 크기의 게임 맵을 갖고 있다. 이는 공간의 개방성을 처음으로 제시한 경우이다. 어디로든 플레이어 마음대로 갈 수 있기 때문에 게임의 진행 방향 또한 덜 선형적이다. 울티마 1은 공간의 개방성뿐만 아니라 이를 이용해 내러티브의 개방성도 일정 부분 보인 것이다.

현대에 이르러서는 거의 한 대도시 규모의 맵을 지닌 게임들이 다수 등장했다. 대표적으로 <GTA> 시리즈, <Just Cause> 시리즈, <Fuel>[Asobo Studio, 2009.] 등이 있다. <Fuel>의 경우 미국이 코네티컷 주를 그대로 구현한 레이싱 게임으로 악명이 높다. 다만, 탁연숙 교수에 의하면 지나치게 큰 맵은 게임의 게임성과 목적성을 해할 가능성도 있다고 한다[탁연숙, 2017 : pp. 111].

## 2. 목표와 규칙의 개방성

다음에 논할 게임은 <엘리트>[David Braben⋅Ian Bell 1984.]라는 게임이다. 이 게임은 우주 비행 시뮬레이터로, 통상적인 게임의 특징보다는, 말 그대로 탐험적인 특징이 더 큰 게임이다. 이 게임은 전투 레벨을 올리는 "엘리트"라는 기본적인 게임의 목표가 있으나, 그것이 게임에서 매우 핵심적으로 작용하지는 않는다. 전투 레벨을 올린다고 해서 한계가 있는 것도 아니고 애초에 게임의 핵심은 '탐험'이기 때문이다. 그렇기에 이 게임은 최초의 Open-Ended Game이라고 불린다. 결말이 없다는 것은 구할 공주도 없고, 구해야하는 세상도 없다. 다시 말하면 게임에 특정한 규칙이나 목표가 존재하지 않거나, 존재하더라도 그것이 게임의 핵심이 아니라는 것이다.

현대에서 목표와 규칙의 개방성이 도드라지게 나타나는 게임이 여럿 있는데, 그 중 가장 대표적인 게임은 <마인크래프트>와 <개리모드>[Facepunch Studios, 2004.]이다. <마인크래프트>는 오픈월드라는 장르를 대중화시킨 게임이다. 이 게임에는 목표도 없으며, 제한적인 규칙 또한 없다. 그저 현실과 매우 비슷하게 제작된 게임 월드에서 하고 싶은 것을 하면 되는 것이다. <마인크래프트>는 생존을 목표로 삼는 서바이벌 모드와 건축을 할 때 자주 사용하는 크레이티브 모드라고 불리는, 일정 부분에선 약하더라도 게임의 목표가 존재하는 반면에, <개리모드>는 아예 그런 것이 없다. 개리모드에선 게임의 규칙이나 목표마저 플레이어가 정하고, 행하는 것이다. <개리모드>는 오픈월드 게임이라고 보기에는 힘들지만, 목표와 규칙의 개방성이 극단적으로 갈 경우, 어떤 형태의 게임이 나오는지 보여주는 훌륭한 예시이다.

목표와 규칙의 개방성에서 가장 중요한 것은 플레이어에게 여러 가지 선택지를 쥐어주는 것이다. 그 이유는 게임의 목표와 규칙을 스스로 선택하는 것은 플레이어가 스스로 무엇을 할 것인지를 선택할 수 있는 가짓수에 대한 자유이기 때문이다[김명호, 2014 : p. 13]. 즉, 가짓수가 많아질수록, 목표와 규칙의 개방성은 더더욱 강해진다고 볼 수 있다. 이 자유도는 단순히 게임 내부에서 여러 가지 행동, 선택뿐만 아니라, 게임 외적으로 사용자들이 직접 게임을 커스터마이징하는 모드(mod)까지 확장된다. 목표와 규칙의 개방성은 당시에는 게임적인 특징을 줄이는 것으로 인식되었다. 게임은 자고로 어떠한 구체적인 목표가 있는데, 이것을 중요하지 않는 것으로 해버리는 것은 게임성을 해치는 것이기 때문이다. 허나, 이 개방성은 후에 오픈월드에 매우 중요한 특징이 되고, 게임성과 재미를 오히려 증가시키는 역할을 하게 된다.

## 3. 캐릭터의 개방성

다음으로 논할 게임은 <엘더 스크롤 2: 대거폴>[Bethesda Softworks, 1996.]이다. <대거폴>은 무려 이탈리아 반도 전체를 덮을 만큼 거대한 게임 월드를 갖고 있어, 세상에서 가장 큰 게임 맵을 갖고 있는 게임으로 유명하다. 헌데 <대거폴>이 오픈월드를 논할 때 중요한 이유는 단순히 그 규모뿐만이 아니다. 기존의 게임의 주인공은 이미 생김새, 성격 등의 특성들이 정립이 된 상태에서 플레이어가 그 캐릭터를 조종하는 방식이었다. <대거폴>의 경우엔 이와는 달리 게임의 시작 지점에서 직접 캐릭터를 생성해야한다. 캐릭터의 생김새, 직업 등과 같은 특성들을 플레이어가 임의로 설정할 수 있다. 이러한 캐릭터 커스터마이징은 오픈월드의 핵심적이고 필수적인 특징은 아니지만, 분명히 게임의 자유도와 몰입도에 많은 영향을 끼친다.[탁연숙, 2017 : p.110] 

캐릭터 커스터마이징은 이후 단순히 <엘더 스크롤> 시리즈뿐만 아니라, RPG적 특징을 갖는 수많은 게임에 이식되었다. 당장 대부분의 온라인 RPG 게임들은 캐릭터 커스터마이징을 지원한다.

## 4. 스토리의 개방성

스토리의 개방성이란 게임의 스토리가 어떤 특정한 방향으로 진행되어야하는 것이 아니라는 의미이다. 대부분의 오픈월드 게임은 하나의 목표에도 많은 멀티 솔루션(multi solutions)의 경우의 수가 존재한다. 단순히 게임 자체에서 여러 경우의 수를 제공하는 것뿐만 아니라, 플레이어 스스로 새로운 솔루션을 생성해낼 수도 있다. [탁연숙, 2017 : p.111] 이 새로운 솔루션은 특히 주변환경과의 상호작용에 의해 생성되는 경우가 흔한데, 이는 오픈월드 특유의 NPC의 인공지능에 의해 이뤄진다. 오픈월드 게임에서는 특히 선형적인 RPG들과는 달리, 게임에 존재하는 NPC들도 게임의 상황에 따라 행동이 다양하게 나타나게 된다. 이 때 게임의 상황이란 플레이어가 NPC에게 미친 영향도 있으나, 게임 월드 자체에 존재하는 NPC나 환경에 영향을 받은 경우도 있다.

플레이어에 의해 NPC가 영향을 받는 경우는 플레이어에 의해 제3의 스토리텔링이 창조되므로 유저는 오히려 게임의 결과보다 창작과정 자체에 매력을 느껴 단순히 게임의 최종목표에 도달하는 것 외에도 과정 자체에 흥미를 느낄 수 있다[탁연숙, 2017 : p.112]. 실제 예시로, <엘더 스크롤 5: 스카이림>[Bethesda Game Studios, 2011.]에서 만약 플레이어가 마을 A에서 존재하는 주민 NPC에게 해를 입히게 된다면, 플레이어는 마을 A의 모든 NPC와 적대 관계가 되며, 현상금이 걸리게 되어 만약 마을 A의 군인과 맞닥뜨리게 된다면 감옥에 가게 되거나, 현상금을 내야한다. 플레이어와 플레이어 이외의 게임 월드의 오브젝트, 대표적으로 NPC와의 상호작용이 중요한 이유는 결국 게임의 진행이라는 것은 사용자의 행동에 따라 진행되기 때문이다[김명호, 2014 : p.17].
또 다른 상호작용은 플레이어 이외의 오브젝트들끼리의 상호작용이다. 이는 주로 NPC들의 AI, 게임 월드의 주변 환경의 디테일에 달려있다. 게임 플레이어와 게임 월드와의 상호작용만큼 강력하지는 않으나, 게임의 몰입도와 디테일에 큰 영향을 줄 수 있다.

## 5. 결론

본장에서의 다룬 내용은 오픈월드가 공간의 개방성, 목표와 규칙의 개방성, 캐릭터의 개방성, 그리고 스토리의 개방성을 주요 특징으로 갖고 있다는 사실이다. 이러한 자유도들은 플레이어에게 계속해서 새롭고 다양한 결과를 가져오는 흥미로운 경험을 제공하고, 게임의 질적 향상은 물론 플레이어에게 몰입감과 만족도를 높이는 중요한 요소가 된다[김명호, 2014 : p.39].

이중에서 본 논문에서 집중적으로 다룰 내용은 인터랙티브 디자인이다. 인터랙티브 디자인은 특히 목표와 규칙의 개방성, 스토리의 개방성에 의해 집중적으로 결정된다. 그렇기 때문에 인터랙티브 디자인을 논하기 위해선 위의 두 가지 개방성을 먼저 논해야한다. 그 이유는 단순히 게임에서의 상호작용을 재미있게 디자인하는 것보다 나중에 가서 게임이 완성됐을 때 그것이 모두 합쳐졌을 때의 결과가 중요하기 때문이다[Tobias Johansson, 2014 : p.13].

# 3. 오픈월드 게임 플레이어 캐릭터 디자인 분석

본장에서는 실제 게임 시장에 출시된 여러 유명 오픈월드 게임들에 대해 그 게임의 인터랙티브 디자인에 대해 분석해보도록 하겠다. 분석을 할 때 집중적으로 제시할 질문은 “어떤 상호작용이 이 게임을 재미있게 만드는가?”이다.

인터랙티브 디자인은 주로 플레이어와 플레이어 외적인 오브젝트간의 상호작용을 중심으로 분석할 것이다. 그 이유는 그것이 상호작용의 제일 핵심적인 부분이기 때문이다. 여기서 핵심적으로 확인해야할 상호작용은 오픈월드이기 때문에 의미가 있는 디자인이다.

## 1. 미들 어스: 섀도우 오브 모르도르

<미들 어스: 섀도우 오브 모르도르>[Monolith Productions, 2014.]는 오픈월드 액션 어드벤처 게임이다. 이 게임에서는 네메시스 시스템이라는 상호작용 시스템이 존재한다. 네메시스 시스템은 사실 <섀도우 오브 모르도르>의 제일 핵심적인 특징이다. 이 시스템을 통해 플레이어는 게임 상의 핵심 적들을 파악하고, 추적할 수 있다. 이 중 제일 오픈월드라는 특징과 연관된 특징은, 단순히 플레이어만이 적을 파악할 수 있는 것이 아닌, 적들 또한 플레이어를 파악할 수 있다는 것이다. 예를 들면, 어떤 적 A가 전에 플레이어를 죽인 적이 있고, 후에 플레이어가 부활하여 다시 A를 만나게 된다면, A는 플레이어에게 죽다 살아났냐고, 다시 죽여주겠다는 말을 한다. 이것이 반복되면 후에는 적들에게 Gravewalker라는 이름으로 불리게 된다. 즉, 죽어도 다시 살아나는 사람이라는 뜻이다. 이것은 단순히 상호작용에만 영향을 주지 않는다. 플레이어를 죽인 적은 적들의 군대 내에서 계급이 올라가게 되고, 플레이어는 이에 자극을 받을 수도 있다. 즉, 당장 플레이어 캐릭터가 아닌 플레이어 자체와도 상호작용이 되는 것이다. 혹자는 그랬다. 플레이어가 감정을 집어넣는 게임이 잘 만든 게임이라고.

또한 이 게임에는 스텔스 기능이 있다. 즉, 적들은 플레이어를 인식할 수 있고, 플레이어는 숨음으로써 이것을 피할 수 있다는 것이다. 이것이 중요한 이유는, 만약 플레이어가 발각이 된다면, 플레이어를 본 적은 이를 다른 적에게 알려 플레이어를 방해하려는 적이 더욱 많아지기 때문이다. 이는 게임 플레이를 다양화시킬 수 있는 행동의 개방성뿐만 아니라 플레이어와의 상호작용을 강화시킨다.
플레이어는 게임에서 제공하는 특수한 능력을 통해 적을 자신의 편을 만들 수 있는데, 이를 통해 서로 이간질을 시킬 수 있다. 이는 플레이어 자신이 직접 게임을 진행하지 않더라도 게임이 진행이 되는 매우 흥미로운 케이스이다. 이 또한 규칙과 행동의 개방성뿐만 아니라 스토리의 개방성을 극대화 시키는 디자인이다.

실제 플레이 경험을 토대로 살펴보면, 역시 네메시스 시스템과 스텔스 시스템이 제일 결정적인 역할을 한다. 게임을 하다가 적들과의 대화를 통해 적들 또한 나의 행동을 인지하고 있고, 적들이 서로 소통을 하면서 플레이어를 대항한다는 점 자체가 게임의 상호작용성을 극대화할 뿐만 아니라 플레이어의 흥미를 돋우고, 몰입감을 극대화시킨다.
