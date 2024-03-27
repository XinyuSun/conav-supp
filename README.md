# CoNav_Supplementary
Supplementary material for the paper "CoNav: A Benchmark for Human-Centered Collaborative Navigation"

## 1. Statistics of CoNav Dataset
### 1.1 Destination Objects

There are *41 destination object* in our dataset, which is parsed from HSSD dataset. This set of destination objects covers a diverse range of items within various rooms.

#### (a) train split

<!-- Bar chart depicting the count of *destination objects* in the training set -->

![](figs/destination_object_bar_chart_train.png)

#### (b) test split

<!-- Bar chart depicting the count of *destination objects* in the test set -->

![](figs/destination_object_bar_chart_test.png)

### 1.2 Objects in Activities

There are *40 objects in activities* within our dataset, which is parsed from LLM-generated data.

#### (a) train split

<!-- Bar chart depicting the count of *objects in activities* within the training set -->

![](figs/grasp_object_bar_chart_train.png)

#### (b) test split

<!-- Bar chart depicting the count of *objects in activities* within the test set -->

![](figs/grasp_object_bar_chart_test.png)

### 1.3 Actions

*76 actions* in our dataset are entirely generated by LLM, which covers various aspects of human life and demonstrates the diversity of action types in our dataset.

#### (a) train split

<!-- Bar chart depicting the count of *action* within the training set -->

![](figs/action_bar_chart_train.png)

#### (b) test split

<!-- Bar chart depicting the count of *action* within the test set -->

![](figs/action_bar_chart_test.png)

### 1.4 Intentions

There are *108 intentions* in our dataset, which is the second-stage activity and is intention-related with first-stage activity.

#### (a) train split

<!-- Bar chart depicting the count of *intention* within the training set -->

![](figs/intention_bar_chart_train.png)

#### (b) test split

<!-- Bar chart depicting the count of *intention* within the test set -->

![](figs/intention_bar_chart_test.png)

### 1.5 Distribution of navigation trajectory length and episode length

Distribution of navigation trajectory length and episode length in the CoNav dataset. ("Trajectory Length" refers to the geodesic distance of the entire navigation trajectory from the starting position to the target object position. "Episode Length" indicates the number of steps in an episode. The dashed lines represent the respective mean values)
- Left: Distribution of agent navigation trajectory length. 
- Middle: Distribution of humanoid navigation trajectory length. 
- Right: Distribution of episode length. 

This figure showcases the diversity in trajectory lengths and episode lengths. These trajectories include activities with both long and short horizons, providing a more comprehensive reflection of the agent's ability to recognize human intentions and assist in task completion.

![](figs/distribution.png)

## 2. Humanoid Animation Results

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


