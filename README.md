# webhacking_tutorial
how to study web hacking, web security

<ol>
  <li> sql injection</li>
  <li> XSS (cross site scripting)</li>
  <li> csrf </li>
  <li> brute force </li>
</ol> 






----------------------------------------
<h3> description </h3>
<h4> This document includes multiple materials for whom wants to study web security in ethical mind. </h4>
<h4 color="red"> 
I am not responsible for any disadvantages if these technologies are not for personal learning, but for any form of abuse. </h4> 



<ol>
  <li> sql injection </li>
   video tutorial by compuphile : <ul> <li> <a href="https://www.youtube.com/watch?v=ciNHn38EyRc">  what is sql injection (17min)</a> </li>
  </ul>
  <ul>
  <li><a href="https://www.youtube.com/watch?v=_jKylhJtPmI"> hacking websites with sqlinjection(9min) </a> </li>
  </ul>
  <ul>
    <li>
  Udemy lectures for koreans: <a href="https://www.udemy.com/everything-about-white-hat-hacker/learn/v4/t/lecture/6386970?start=0"> 화이트 해커를 위한 8가지 웹해킹 기법 </a><li>
  <li>
  칼리리눅스, dvwa, xampp 웹해킹 환경설정 <a href="https://sonofgodcom.wordpress.com/2018/11/19/kali-linux-xampp-dvwa-%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95/"> personnel blog </a><li> 

 </ul>
 </ol> 
 
 <h3> 공부방법 </h3>
 <h4>아래의 글은 <a href="http://www.hackerschool.org/HS_Boards/zboard.php?id=QNA_job&no=674"> 해커스쿨에서</a> 가져온 글입니다. </h4>
<h5>  
1. 입문 단계<br/> 
입문단계에서는 보안분야의 모든 분야를 경험해보는것이 중요합니다
모든걸 이해하는게 중요한것은 아니고, 해킹에는 여러분야가 있는데, 그 분야들을 알아감과 동시에
각 분야를 공부하기 위해선 컴퓨터 이외의 어떤 것들을 공부하는것이 좋은지 알아가는 시간이 필요합니다
컴퓨터 분야 이외의 기본을 소홀히 하다가 예를들어 수학, 영어, 과학때문에 발목잡히는 경우가 많기 때문이죠
예를들어서 암호학은 정수론을 이해하지 못하면 깨작거리는 수준에서 벗어날 수 없고
컴퓨터 그래픽스라면 물리학, 미적분학등을 이해하지 못하면 마찬가지로 낮은 수준에서 벗어날 수 없습니다
그리고 선형대수학을 이해하지 못하면 머신러닝을 할 때 기초없이 하게되어 수준높은 활용과 문제해결이 어렵습니다

2. 기초 단계<br/>
입문단계에서 경험한 많은 분야들의 기초를 모두 경험해보세요
예를들어 시스템해킹이라면 FTZ, overthewire.org의 저수준문제들을 클리어해보세요
웹해킹이라면 webhacking.kr, 혹은 Lord of SQL 1단계를 모두 클리어해보세요
리버싱이라면 codeengn.com 의 기초단계 혹은 reversing.kr 의 저배점 문제들을 모두 클리어해보세요
암호학이라면 http://cryptopals.com/ 여깄는 문제들을 모두 코딩해보세요
포렌식은 워게임으로써 접하기는 어려울것같고 디지털포렌식 전문가 2급 자격증을 목표로 공부해보세요

그리고 과학은 나중에 진로를 정하실때 뭘 정하시느냐에 따라 다르기때문에 그냥 알아서 하시면 되고
수학은 최대한 빨리 공부하시는게 좋습니다.
해킹공부를 아무리 빨리해도 수학공부를 제쳐둔다면 해킹공부의 한계에 빠르게 다다르고, 한계에 다다랐을때는 수학공부때문에 3년이상 남들보다 뒤쳐지기 때문에 성장속도가 더디게됩니다
수학은 그냥 한계 없이 쭉 수학의 모든 분야를 다 공부한단 생각으로 공부하시면 됩니다

여기까지 하시면 1년에서 1년반정도가 걸리실겁니다
그러면 중3~고1정도 되실텐데, BoB 사업이 그때까지 진행된다는 전제하에, 고등학교 1학년부터 BoB에 지원이 가능합니다(kitribob.kr). 하지만 이 상태에서 비오비를 들어가시면 공부 효율이 그렇게 좋진 않을겁니다

3. 중급 단계<br/>
여기서부터는 모든 분야를 한번에 진행하기는 무리가 있습니다. 위의 과정을 지나오면서 제일 자기가 잘하는 분야가 생겼을겁니다.
그 분야의 약 5년전 대회문제들을 찾아서(shell-storm.org 의 Repository, github.com/ctfs/ 의 writeup에도 문제가 있습니다)
쭉 풀어봅니다. 5년전것들을 다풀었으면 4년전것들, 3년전것들, 2년전, 1년전 그리고 올해 초에 진행됐던 대회문제들을 쭉 풀어봅니다.
그렇게 하면서 열리는 대회들에 다 등록을 해서 문제를 풀어봅니다
물론 문제가 처음엔 안풀릴테니, 혼자서 공부하고 이해하는 시간과 인터넷에서 풀이를 보고 공부하는 시간의 밸런스를 잘 맞춰야합니다.
저같은 경우에는 문제가 안풀릴땐 최대 한달까지 혼자 보고, 만약 그게 나중에 봐도 안풀릴것같다면 풀이를 보고, 나중에 보면 풀릴것같다 라고 생각하면 다른 문제를 먼저 봅니다

4. 고급 단계<br/>
중급단계에서 처럼 대회문제를 공부하면 대회에선 크게 뒤쳐지지 않을 수 있습니다. 그럼 이제 슬슬 리얼월드의 것을 할 차례죠
리얼월드는 약간 다릅니다. 취약점을 찾더라도 대회문제처럼 딱 여기에 취약점이 있으니 분석하세요 이런 느낌도 아니고, 정말 사람의 실수에 의해서, 그리고 구조상 문제로 인해서 생긴 취약점들을 찾아야 하기 때문에 해당 프로그램의 유형에 대한 이해가 깊어야합니다
저는 이때 BoB를 하는것을 추천합니다.
이때부터는 약간 신기술처럼 보이는것들도 이해하는데 큰 문제가 없습니다. (한 2~3년 공부했을때입니다)
비오비를 하면서 최신 논문들도 많이 읽어보고, 내가 가고자하는 이 길에서 어려운것이 뭔지, 그리고 나에게 그걸 해결하기 위한 아이디어가 있는지, 이런것들을 알 수 있는 시간입니다
실제로 보안업계는 발전이 굉장히 빠릅니다.
발전이 빠르단 얘기는 아직도 미개척 시장이 많고 분야가 많다는 뜻입니다
즉 어느정도 궤도에 오르기만 한다면 본인이 직접 미개척분야를 개척하며 공부할 수도 있다는 거죠
비오비를 하시게 되면 그 기반을 다지기에 굉장히 수월합니다
</h5>
  
