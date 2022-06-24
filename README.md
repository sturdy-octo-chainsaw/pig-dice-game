# pig-dice-game

[Comparing Policies]

Throughout the paper, 
we measure the performance of policies against
the optimal policy of Neller and Presser [2004]. 
In this section, we describe the technique.

Let Roll A i,j,k and Roll B i,j,k 
be Boolean values indicating whether or not
player A and player B, 
respectively, 
will roll given a score of i, an opponent score of j, and a turn total of k. 

Then we can define the respective
probabilities of winning in these states, P A i,j,k and P B i,j,k, as follows:

## 1이 되면 초기화

### 설명


- 앞 내용 : : 랜덤으로 던져 1을 제외하고 합산 ( 단 계속 던질지 플레이어가 선택)

- 초기화 : 1이 나오면 합산 된 숫자 초기화 > 플레이어 턴이 넘어감
