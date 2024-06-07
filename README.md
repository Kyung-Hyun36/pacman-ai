# pacman 사용법
(1) $ python2.7 gridworld.py -h
    - 팩맨 게임을 실행합니다.


## pacman 옵션
(1) -h, --help

= 도움말 메시지를 보여줍니다.


(2) -d DISCOUNT, --discount=DISCOUNT

= Discount on future (default 0.9)


(3) -r R, --livingReward=R

= Reward for living for a time step (default 0.0)


(4) -n P, --noise=P

= How often action results in unintended direction (default 0.2)


(5) -e E, --epsilon=E 

= Chance of taking a random action in q-learning (default 0.3)


(6) -l P, --learningRate=P

= TD learning rate (default 0.5)


(7) -i K, --iterations=K

= Number of rounds of value iteration (default 10)


(8) -k K, --episodes=K

= Number of epsiodes of the MDP to run (default 1)


(9) -g G, --grid=G

= Grid to use (case sensitive; options are BookGrid, BridgeGrid, CliffGrid, MazeGrid, default BookGrid)


(10) -w X, --windowSize=X

= Request a window width of X pixels *per grid cell* (default 150)


(11) -a A, --agent=A

= Agent type (options are 'random', 'value' and 'q', default random)


(12) -t, --text

= Use text-only ASCII display


(13) -p, --pause

= Pause GUI after each time step when running the MDP


(14) -q, --quiet

= Skip display of any learning episodes


(15) -s S, --speed=S

= Speed of animation, S > 1.0 is faster, 0.0 < S < 1.0 is slower (default 1.0)


(16) -m, --manual

= Manually control agent


(17) --v, --valueSteps

= Display each step of value iteration