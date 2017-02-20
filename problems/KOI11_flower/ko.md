오늘은 공주님이 태어난 경사스러운 날이다. 왕은 이 날을 기념하기 위해 늘 꽃이 피어있는 작은 정원을 만들기로 결정했다.

총 $N$개의 꽃이 있는데, 꽃은 모두 같은 해에 피어서 같은 해에 진다. 하나의 꽃은 피는 날과 지는 날이 정해져 있다. 예를 들어, 5월 8일 피어서 6월 13일 지는 꽃은 5월 8일부터 6월 12일까지는 꽃이 피어 있고, 6월 13일을 포함하여 이후로는 꽃을 볼 수 없다는 의미이다. (올해는 4, 6, 9, 11월은 30일까지 있고, 1, 3, 5, 7, 8, 10, 12월은 31일까지 있으며, 2월은 28일까지만 있다.)

이러한 $N$개의 꽃들 중에서 다음의 두 조건을 만족하는 꽃들을 선택하고 싶다.

1. 공주가 가장 좋아하는 계절인 3월 1일부터 11월 30일까지 매일 꽃이 하나 이상 피어 있도록 한다.
2. 정원이 넓지 않으므로 정원에 심는 꽃들의 수를 가능한 적게 한다. 

여러분은 $N$개의 꽃들 중에서 위의 두 조건을 만족하는, 즉 3월 1일부터 11월 30일까지 매일 꽃이 한 가지 이상 피어 있도록 꽃들을 선택할 때, 선택한 꽃들의 최소 개수를 출력하는 프로그램을 작성하시오. 

실행시간은 1초를 넘을 수 없으며, 각 데이터에 대해 부분 점수는 주어지지 않는다.

### 입력 형식

첫째 줄에는 꽃들의 총 개수 $N$이 주어진다. 다음 개의 줄에는 각 꽃이 피는 날짜와 지는 날짜가 주어진다. 하나의 날짜는 월과 일을 나타내는 숫자로 표현된다. 예를 들어서, 3 8 7 31은 꽃이 3월 8일에 피어서 7월 31일에 진다는 것을 나타낸다. 

### 출력 형식

첫째 줄에 선택한 꽃들의 최소 개수를 출력한다. 만약 두 조건을 만족하는 꽃들을 선택할 수 없다면 0을 출력한다.

### 서브태스크

각 서브태스크의 점수는 맞은 데이터의 개수에 비례하게 주어집니다.

#### 서브태스크 1 (20점)

$1 \le N \le 30$.

#### 서브태스크 2 (30점)

$1 \le N \le 10,000$.

#### 서브태스크 3 (50점)

$1 \le N \le 100,000$.

### 입력과 출력의 예

<table class='table table-bordered table-condensed'>
 <thead>
  <tr>
   <th style="width: 50%;">입력</th>
   <th style="width: 50%;">출력</th>
  </tr>
 </thead>
 <tbody class="code-font">
  <tr>
   <td>4<BR/>
1 1 5 31<BR/>
1 1 6 30<BR/>
5 15 8 31<BR/>
6 10 12 10</td>
   <td>2</td>
  </tr>
  <tr>
   <td>10<BR/>
2 15 3 23<BR/>
4 12 6 5<BR/>
5 2 5 31<BR/>
9 14 12 24<BR/>
6 15 9 3<BR/>
6 3 6 15<BR/>
2 28 4 25<BR/>
6 15 9 27<BR/>
10 5 12 31<BR/>
7 14 9 1</td>
   <td>5</td>
  </tr>
 </tbody>
</table>