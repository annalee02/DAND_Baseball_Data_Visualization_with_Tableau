# Project Links

* [Project Viz: 1,157 Major League Baseball players_initial](https://public.tableau.com/profile/anna8185#!/vizhome/ProjectViz1157Baseballplayers/Story)
* [Project Viz: 1,157 Major League Baseball players_final](https://public.tableau.com/profile/anna8185#!/vizhome/ProjectViz1157MajorLeagueBaseballplayers_final/Story?publish=yes)

## Summary
In the workbook, there is a story to convey important findings about 1,157 baseball players. The data used in this workbook contains their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and number of home runs. The story shows how baseball players in each handedness category differ and whether their weight or height has influenced players' performance.

## Initial Design

* Home Run Leaders:

|Design                |Choices                 |
|---------------------:|-----------------------:|
|Chart type            |Horizontal bars         |
|Visual encodings      |Length, Color saturation|
|Legends               |Color (Home runs)       |

**Reason for selection**: The main reason that I chose a bar chart is to __compare__ one variable, "Home runs" with a few items such as "Handedness" and "Name".  To do this, a horizontal bar was a better choice than vertical one so that rows can have several items. Since "Home runs" is ordered data, I chose length and color saturation as visual encodings.

* Top 10 Performers:

|Design                |Choices                 |
|---------------------:|-----------------------:|
|Chart type            |Packed bubbles          |
|Visual encodings      |Size, Color hue         |
|Legends               |Color (Handedness)      |

**Reason for selection**: Bubble chart is perfect to show __relationships__ between 3 variables including "Name", "Handedness", and "Home runs times Batting Average". Color hue was chosen for "Handedness" because it is nominal data.

* Height and Weight:

|Design                |Choices                   |
|---------------------:|-------------------------:|
|Chart type            |Scatter plot              |
|Visual encodings      |Color saturation, position|
|Legends               |Color (Homeruns times Batting Average)|

**Reason for selection**: This Scatter plot is to show the data __distribution__. It helps me to display not only median with quartiles but also each data point's position(height and weight) and color (performance score).

* Home runs vs. Batting Avg:

|Design                |Choices                   |
|---------------------:|-------------------------:|
|Chart type            |Scatter plot              |
|Visual encodings      |Color hue, shape, position|
|Legends               |Color, Shape (Handedness) |

**Reason for selection**: I used color hue and shape at the same time for "Handedness" in order to figure out each group's  position (__distribution__) and trend easily with regards to their performance.

* Dashboard 1: Top 10 Performers + Home runs vs. Batting Avg
* Dashboard 2: Height and Weight + Home Run Leaders
* Story: Dashboard 1 + Dashboard 2

## Feedback

1.	Home run leaders 에서 각각 5명씩 표본이 나와있는데 어떠한 기준으로 뽑은 것인지 알 수 없다. \
: It's not clear why those 5 players in each category were selected in "Home run leaders".

2.	Top 10 performers 에서 상위 10명이라 명시해놓고 표시되는 선수는 10명 이상이라는 점. 또한, 아무래도 선수들간의 수치가 엄청 크게 차이가 나는 것이 아니기에 원의 크기들이 조금 비슷해 보인다. 이름을 표기 안 해주었다면 탑10을 알아보기 힘들었을 것 같다. \
: The title is "Top 10 performers", but there are more than 10 players with a name shown in the graph. Since there wasn't a big difference between player's performance scores, each bubble size is similar to another. If it didn't show a player's name, it would be hard to find which one is in Top 10.

3.	Homerun leaders / top 10 performers / homeruns vs batting / height and weight 순이 더 나을 듯! \
: [Homerun leaders / top 10 performers / homeruns vs batting / height and weight] would be a better sequence!

4.	Dashboard 2 와 story 에서 두 별개의 자료를 같이 나열한 이유가 무엇인지. 연관성이 떨어지는 두 자료를 함께 삽입하고 위의 자료에 대한 결과만 적은 점 \
: I wonder why 2 different graphs are placed on the Dashboard 2. 2 unrelated visualizations were inserted in the story and you explained only about the first graph.


## Final Design
* Home Run Leaders: Rank measure is created and added to the visualization as a third row so that a reader can easily figure out why those players were selected in the graph.
* Top 10 Performers: The error is fixed to correctly show only Top 10 players' names in the bubbles.
* Sheet sequence: Home Run leaders > top 10 performers > homeruns vs batting > height and weight. First 3 sheets are related so "Height and Weight" sheet moved to the 4th.
* Dashboard 2: "Home Run Leaders" is removed from the dashboard since it is not related to "Height and Weight".
* Story: "Home Run Leaders" sheet is added to the story.
