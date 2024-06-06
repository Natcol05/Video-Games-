<p align="center"><b>Decoding the Video Game Industry: Strategies for Successful Launches</b></p>

This project aims to identify patterns that could forecast the success or failure of video game releases, thereby aiding in the planning of future advertising campaigns.
The dataset provided encompasses a wealth of information, including user and expert reviews, game genres, platforms, historical sales data, and ESRB ratings. The analysis was conducted by region, considering North America, Europe, Japan, and other regions, and across different platforms like Wii, Xbox360, and all versions of PlayStation up to version 6.

These are some of the libraries used in the project:

```python
import pandas as pd
import numpy as np
from matplotlib import pyplot as plt
import math as mt
from PIL import Image
import seaborn as sb
from scipy.stats import ttest_ind
```

And here is the dataset used for the analysis:

- <b>Video Games</b>: This dataset encompasses information about multiple video games released between 1980 and 2016. It includes details such as the release year, the platform (like PS4, Xbox One, PC), user and critic ratings, and sales figures across different regions (North America, Europe, Japan, and other regions) ([Click Here](https://github.com/Natcol05/Video-games-/blob/d3e925721d66b17c8aea43e7761d9ddee0f8c3de/games%20(1).csv))

**In general terms, the conclusions indicate that:**

* Considering the specific characteristics of the target market is crucial, as each region has different dynamics.

* Creating a video game that aligns with the most popular genres in the target market can significantly impact its success. Additionally, the choice of platform is important.

* However, when it comes to platforms, it's necessary to consider the year of release as a factor that can influence sales leadership.

* Finally, the relationship between critics' reviews and video game sales is not very clear, so it's not necessarily a determining factor.

