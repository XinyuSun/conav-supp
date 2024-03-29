# CoNav Supplementary for Rebuttal
This is the supplementary material for paper "CoNav: A Benchmark for Human-Centered Collaborative Navigation"

We organize our supplementary material as follows:
- In Section [A](#jump-A), we provide the statistics of destination objects.
- In Section [B](#jump-B), we provide the statistics of activity objects.
- In Section [C](#jump-C), we provide the statistics of human actions.
- In Section [D](#jump-D), we provide the statistics of human activities.
- In Section [E](#jump-E), we demonstrate the distribution of navigation trajectory lengths and episode steps.
- In Section [F](#jump-F), we provide more qualitative results of generated humanoid animations.
- In Section [G](#jump-F), we provide more qualitative results of agent navigation.

<!-- ## 1. Statistics of CoNav Dataset -->
### A. Statistics of Destination Objects
<span id="jump-A"></span>

The destination objects are utilized to identify the human destination, for example, *"the human takes a book from the **bookrest**"*. In the training split, there are *40 types of destination objects* while the test split features *34 types*, 33 of which are overlapped. 
<!-- In each scene, we select multiple navigable destination objects to construct destination object set $\mathbf{O}_D$. Then we instruct the LLM to pick a destination object and generate an activity that make sense. -->


#### (a) Training split

<!-- Bar chart depicting the count of *destination objects* in the training set -->

![](figs/destination_object_bar_chart_train.png)

#### (b) Test split

<!-- Bar chart depicting the count of *destination objects* in the test set -->

![](figs/destination_object_bar_chart_test.png)

### B. Statistics of Activity Objects
<span id="jump-B"></span>

The activity objects are interaction targets in the generated human activities, for example, *"the human takes a **book** from the bookrest"*. In the training split, there are *39 types of destination objects* while the test split features *37 types*, 36 of which are overlapped.
<!-- There are *40 objects in activities* within our dataset, which is parsed from LLM-generated data. -->

#### (a) Training split

<!-- Bar chart depicting the count of *objects in activities* within the training set -->

![](figs/grasp_object_bar_chart_train.png)

#### (b) Test split

<!-- Bar chart depicting the count of *objects in activities* within the test set -->

![](figs/grasp_object_bar_chart_test.png)

### C. Actions
<span id="jump-C"></span>

There are 76 types of human actions in all LLM-synthesized activities, for example, *"the human **takes** a book from the bookrest"*. In the training split, there are *75 types* while the test split features *70 types*, 69 of which are overlapped.
<!-- *76 actions* in our dataset are entirely generated by LLM, which covers various aspects of human life and demonstrates the diversity of action types in our dataset. -->

#### (a) Training split

<!-- Bar chart depicting the count of *action* within the training set -->

![](figs/action_bar_chart_train.png)

#### (b) Test split

<!-- Bar chart depicting the count of *action* within the test set -->

![](figs/action_bar_chart_test.png)

### D. Human Activities
<span id="jump-D"></span>

We summarize the statistic of 101 unique LLM-synthesized human activities in this section, for example, *"**the human takes a book from the bookres**t"*. In the training split, there are *97 types* while the test split features *88 types*, 84 of which are overlapped.
<!-- There are *108 intentions* in our dataset, which is the second-stage activity and is intention-related with first-stage activity. -->

#### (a) Training split

<!-- Bar chart depicting the count of *intention* within the training set -->

![](figs/intention_bar_chart_train.png)

#### (b) Test split

<!-- Bar chart depicting the count of *intention* within the test set -->

![](figs/intention_bar_chart_test.png)

### E. Distribution of navigation trajectory lengths and episode steps
<span id="jump-E"></span>

In this section, we demonstrate the distribution of navigation trajectory lengths and episode steps in the CoNav dataset. ("Trajectory Lengths" refers to the geodesic distance of the entire navigation trajectory from the starting position to the target object position. "Episode Steps" indicates the number of steps in an episode. The dashed lines represent the respective mean values)
- Left: Distribution of agent navigation trajectory lengths. 
- Middle: Distribution of humanoid navigation trajectory lengths. 
- Right: Distribution of episode steps. 

This figure showcases the diversity in trajectory lengths and episode steps. These trajectories include activities with both long and short horizons, providing a more comprehensive reflection of the agent's ability to recognize human intentions and assist in task completion.

![](figs/distribution.png)

## F. Qualitive Results of Humanoid Animation
<span id="jump-F"></span>

<!-- <div style="text-align: center;">

  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_cleans_brushes_at_the_sink.png" style="width: 100%;">
    <p>A person cleans brushes at the sink.</p>
  </div>
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_exercises_on_the_treadmill.png" style="width: 100%;">
    <p>A person exercises on the treadmill.</p>
  </div>
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_picks_up_a_toothbrush_from_the_sink.png" style="width: 100%;">
    <p>A person picks up a toothbrush from the sink.</p>
  </div>
</div>

<div style="text-align: center;">
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_takes_a_water_bottle_from_the_table.png" style="width: 100%;">
    <p>A person takes a water bottle from the table.</p>
  </div>
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_takes_books_from_the_shelves.png" style="width: 100%;">
    <p>A person takes books from the shelves.</p>
  </div>
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_dresses_in_front_of_the_mirror.png" style="width: 100%;">
    <p>A person dresses in front of the mirror.</p>
  </div>
</div>

<div style="text-align: center;">
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_gardens_near_the_potted_plant.png" style="width: 100%;">
    <p>A person gardens near the potted plant.</p>
  </div>
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a_person_showers_in_the_shower.png" style="width: 100%;">
    <p>A person showers in the shower.</p>
  </div>
  <div style="display: inline-block; width: 30%; margin: 0 1%;">
    <img src="figs/a person picks out clothes from the wardrobe.png" style="width: 100%;">
    <p>A person picks out clothes from the wardrobe.</p>
  </div>
</div> -->

<table style="width: 100%; text-align: center;">
  <tr>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_cleans_brushes_at_the_sink.png" style="width: 100%;">
      <p>A person cleans brushes at the sink.</p>
    </td>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_exercises_on_the_treadmill.png" style="width: 98%;">
      <p>A person exercises on the treadmill.</p>
    </td>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_picks_up_a_toothbrush_from_the_sink.png" style="width: 97%;">
      <p>A person picks up toothbrush from the sink.</p>
    </td>
  </tr>
</table>

<table style="width: 100%; text-align: center;">
  <tr>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_takes_a_water_bottle_from_the_table.png" style="width: 100%;">
      <p>A person takes a bottle from the table.</p>
    </td>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_takes_books_from_the_shelves.png" style="width: 100%;">
      <p>A person takes books from the shelves.</p>
    </td>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_dresses_in_front_of_the_mirror.png" style="width: 100%;">
      <p>A person dresses in front of the mirror.</p>
    </td>
  </tr>
</table>

<table style="width: 100%; text-align: center;">
  <tr>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_gardens_near_the_potted_plant.png" style="width: 100%;">
      <p>A person gardens near the potted plant.</p>
    </td>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a_person_showers_in_the_shower.png" style="width: 100%;">
      <p>A person leisurely showers in the shower.</p>
    </td>
    <td style="width: 30%; padding: 0 0%;">
      <img src="figs/a person picks out clothes from the wardrobe.png" style="width: 96%;">
      <p>A person picks out clothes from the wardrobe.</p>
    </td>
  </tr>
</table>

### Complete Action Display
<p align="center">
  <img src="figs/a_person_takes_a_water_bottle_from_the_table_a_person_hydrates_on_the_treadmill.png"  width="100%"/>
  <br>
  A person takes a water bottle from the table.
  <br>
  A person hydrates on the treadmill.
  <br>
</p>

<p align="center">
  <img src="figs/a_person_grabs_gardening_tools_from_the_cabinet_a_person_gardens_near_the_potted_plant.png"  width="100%"/>
  <br>
  A person grabs gardening tools from the table.
  <br>
  A person gardens near the potted plant.
  <br>
</p>

<p align="center">
  <img src="figs/a person takes a broom from the cabinet_a person cleans the carpet_1.png"  width="100%"/>
  <br>
  A person takes a broom.
  <br>
  A person cleans the carpet.
  <br>
</p>


## G. Visualization Results for Navigation
<span id="jump-F"></span>

### G-1. Failure Cases of Pioneer Agent

#### (a) conflicts with human actions, leading to collisions

![](figs/pioneer_agent_collision_1.png)

![](figs/pioneer_agent_collision_2.png)

#### (b) heuristic algorithm occasionally plans waypoints that are not navigable, making the agent stuck

![](figs/pioneer_agent_stuck_1.png)

![](figs/pioneer_agent_stuck_2.png)
