# 0. 요약
    파이썬을 활용해서 6가지 미니게임을 만들었습니다. 
    하나는 너무 간단한 것 같아 6가지 게임 중 골라할 수 있게 제작했습니다. 
    게임은 숫자야구, 행맨, 틱택토, 가위바위보, 숫자 추측 게임, 메모리 게임이 있습니다. 
    mini game code에 있는 코드를 복사해 실행하면 게임이 즉시 실행됩니다. 
    별도의 UI가 나타나도록 했으며 소소하게 시간을 보낼 때 유용할 것입니다. 사용된 코드들은 구글을 참고했습니다.  
# 1. 숫자야구
    숫자야구는 컴퓨터가 선정한 임의의 4자리 숫자를 맞히는 게임입니다. 자리와 숫자가 모두 맞는경우 스트라이크로, 숫자만 맞는 경우에는 볼로 표시되며 둘 다 맞지 않는 경우에는 표시되지 않습니다. (ex. 임의의 숫자 1234 / 사용자 제시 숫자 1547 / 결과 1 스트라이크 1 볼 ) 편의를 위해 이전에 제시했던 숫자와 결과를 기록창에서 확인할 수 있으며 사용자가 숫자를 맞히면 게임이 종료됩니다. 'O번만에 성공하셨습니다.'는 결과 창이 나오므로 친구들과 대결하기 좋은 게임입니다.
# 2. 행맨(HANG MAN)
    행맨은 컴퓨터가 선정한 임의의 영어단어를 맞히는 게임입니다. 총 6번의 기회가 주어지고 컴퓨터가 선정한 단어의 길이는 제공됩니다. 사용자는 알파벳을 하나씩 제시해서 단어를 맞혀나가면 되고 정답에 포함된 알파벳을 맞히는 경우에는 기회가 차감되지 않습니다. 주어진 기회 안에 맞히는 것이 생각보다 까다로우며 아는 영어단어가 많지 않다면 게임에서 승리하기 힘들 것 입니다.
# 3. 틱택토
    틱택토는 사용자와 컴퓨터가 번갈아 가며 3x3 격자에 자신의 마크(X 또는 O)를 놓아 수평, 수직 또는 대각선으로 3개의 마크를 연속으로 나열하는 것을 목표로 하는 게임입니다. 이 게임은 간단하면서도 전략적인 요소가 있어 누구나 쉽게 즐길 수 있습니다.
# 4. 가위바위보
    가위바위보는 우리가 흔히 아는 가위바위보입니다. 사용자가 가위, 바위, 보 중에 하나를 고르면 컴퓨터가 고른 것과 비교하여 결과를 보여줍니다. 3판 2선승으로 2번을 먼저 이기면 게임에서 승리하며 비길 수도 있습니다.
# 5. 숫자 추측 게임
    숫자 추측 게임은 1부터 100사이의 숫자 중에 컴퓨터가 임의로 정한 숫자를 맞히는 게임입니다. 사용자가 숫자를 제시하면 정답이 제시한 숫자보다 큰지 작은지를 알려주며 해당 정보를 통해 숫자를 유추해 나가면 됩니다. 숫자를 맞히면 'O번만에 성공하셨습니다.'는 결과 창이 나옵니다.
# 6. 메모리 게임
    메모리 게임은 15쌍의 같은 그림의 카드를 찾는 게임입니다. 사용자는 뒤집어진 30장의 카드중에서 두장을 선택할 수 있으며 두 장의 카드가 같은 카드인 경우 다시 뒤집어지지 않고 다른 카드인 경우에는 다시 뒷면으로 뒤집어집니다. 기억력을 최대한 활용해 빠른 시간 안에 모든 카드를 뒤집는 게임입니다.
