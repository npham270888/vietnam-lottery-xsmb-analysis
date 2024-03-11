# Vietnam Lottery (XSMB) Analysis

Using GitHub Action to automatically fetch and analyze results of the Vietnam lottery daily.

Download:

* [Full data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb.csv)
* [1-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_1_year.csv)
* [2-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_2_year.csv)
* [3-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_3_year.csv)
* [5-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_5_year.csv)

| Lotery      | Loto |
| :-----------: | :-----------: |
| <table><tr><td>Date</td><td>11-03-2024</td></tr><tr><td>Special</td><td>68333</td></tr><tr><td>First</td><td>15214</td></tr><tr><td>Second</td><td>41437, 19271</td></tr><tr><td rowspan="2">Third</td><td>81367, 05175, 83589</td></tr><tr><td>47586, 69646, 07575</td></tr><tr><td>Fourth</td><td>7285, 1688, 9707, 9289</td></tr><tr><td rowspan="2">Fifth</td><td>0140, 6399, 9619</td></tr><tr><td>3239, 3428, 9131</td></tr><tr><td>Sixth</td><td>438, 211, 465</td></tr><tr><td>Seventh</td><td>99, 79, 10, 72</td></tr></table> | <table><tr><td>First</td><td>Last</td></tr><tr><td>0</td><td>7</td></tr><tr><td>1</td><td>0, 1, 4, 9</td></tr><tr><td>2</td><td>8</td></tr><tr><td>3</td><td>1, 3, 7, 8, 9</td></tr><tr><td>4</td><td>0, 6</td></tr><tr><td>5</td><td>-</td></tr><tr><td>6</td><td>5, 7</td></tr><tr><td>7</td><td>1, 2, 5, 5, 9</td></tr><tr><td>8</td><td>5, 6, 8, 9, 9</td></tr><tr><td>9</td><td>9, 9</td></tr></table> |


<h2>Analysis of special prices</h2>

<h3>Amount of day from last appearing</h3>

![Delta](images/special_delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/special_delta_top_10.jpg)

<h2>Analysis of one-year results</h2>

Max: 118. Min: 79.

Mean: 97.74. Standard deviation: 8.83.

<h3>Detail</h3>

![Detail](images/heatmap.jpg)

<h3>Top 10</h3>

![Top 10](images/top-10.jpg)

<h3>Distribution</h3>

![Distribution](images/distribution.jpg)

<h2>Amount of day from last appearing</h2>

![Delta](images/delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/delta_top_10.jpg)