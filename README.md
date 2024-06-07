# pacman 사용법
(1) $ python2.7 pacman.py
    - 팩맨 게임을 실행합니다.

(2) $ python2.7 pacman.py -l smallClassic -z 2
    - 더 작은 보드에서 팩맨 게임을 실행하고, 창을 확대합니다.


## pacman 옵션
(1) -h, --help

= 도움말 메시지를 보여줍니다.


(2) -n GAMES, --numGames=GAMES

= 게임을 실행할 횟수를 정합니다.

    python2.7 pacman.py -n 3


(3) -l LAYOUT_FILE, -layout=LAYOUT_FILE

= 게임의 지도 레이아웃을 로드할 Layout 파일을 설정합니다. [기본값 : mediumClassic]

    python2.7 pacman.py -l smallClassic

(레이아웃 종류는 /pacman/layouts 폴더에서 확인 가능합니다.)


(4) -p TYPE, --pacman=TYPE

= 사용할 pacmanAgents 모듈의 타입을 설정합니다. [기본값 : KeyboardAgent]

    python2.7 pacman.py -p LeftTurnAgent


(5) -t, --textGraphics

= 출력을 텍스트로만 표시합니다.


(6) -q, --quietTextGraphics

= 최소한의 출력과 그래픽 없이 생성합니다.


(7) -g TYPE, --ghosts=TYPE

= 사용할 ghostAgents 모듈의 타입을 설정합니다. [기본값 : RandomGhost]

    python2.7 pacman.py -g DirectionalGhost


(8) -k NUMGHOSTS, --numghosts=NUMGHOSTS 

= 사용할 최대 ghost 수를 설정합니다 [기본값 : 4]

    python2.7 pacman.py -k 1


(9) -z ZOOM, --zoom=ZOOM

= 그래픽 창의 크기를 설정합니다. [기본값 : 1.0]

    python2.7 pacman.py -z 2


(10) -f, --fixRandomSeed

= 항상 같은 게임을 하도록 시드를 고정합니다.


(11) -r, --recordActions

= 게임 기록을 파일에 기록합니다. (파일명은 플레이한 시간)


(12) --replay=GAMETOREPLAY

= 기록된 게임 파일을 실행합니다. (다시 보기 느낌)


(13) -a AGENTARGS, --agentArgs=AGENTARGS

= 에이전트에 보낸 쉼표로 구분된 값을 적용합니다.


(14) -x NUMTRAINING, --numTraining=NUMTRAINING

= 트레이닝 중인 에피소드 수를 설정합니다 (출력 억제) [기본값 : 0]


(15) --frameTime=FRAMETIME

= 프레임 간 지연시간, <0은 키보드를 의미합니다. [기본값 : 0.1]

    python2.7 pacman.py --frameTime=-0.1


(16) -c, --catchExceptions

= 게임 중 예외 처리 및 시간 제한을 켭니다.


(17) --timeout=TIMEOUT

= 에이전트가 단일 게임에서 컴퓨팅에 소비할 수 있는 최대 시간을 설정합니다. [기본값 : 30]