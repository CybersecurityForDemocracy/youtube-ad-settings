# More and Scammier Ads: The Perils of YouTube’s Ad Privacy Settings

## Abstract 

When users disable online ad personalization, they might be anticipating to see fewer ads that are "relevant" to them as a trade-off for more privacy. In this paper, we show that the tradeoff can go much further than this intuition. We conducted controlled experiments on YouTube in Australia, Canada, Ireland, the United Kingdom, and the United States to investigate the impact of disabling ad personalization on the quantity and quality of ads that users receive.

Through experiments where emulated users with different ad privacy settings watched sequences of 400 videos, we show that disabling ad personalization can lead to the user being shown as much as 1.30 times more pre-roll ads than the default (least private) setting. More concerning is that in our experiments, the proportion of predatory ads increased 2.69 times compared to the default setting, from 2.5% to 8.7% of ads. This result highlights that certain user demographics (in this case, privacy-conscious users) can be exposed to significantly higher rates of predatory ads, and suggests that the platform's efforts to curb such ads are still falling short.

## Labeled Ads Dataset
The `labeled_ads` folder contains the dataset in CSV format, accompanied by a PDF codebook and a description of the labeling methodology (both also included in the paper).

The dataset contains 30,237 unique YouTube video ads (4.23MB), each labeled with a binary indicator of whether it was considered predatory. A README file is included to explain the dataset columns.

## Contact
If you publish work using the data in this repository, please cite the paper as follows:
```
@article{mai2025youtubescamads,
  title={More and Scammier Ads: The Perils of YouTube's Ad Privacy Settings},
  author={Mai, Cat and Coelho, Bruno and Kieserman, Julia and Matsumoto, Lexie and Spinelli, Kyle and Yang, Eric and Andreou, Athanasios and Greenstadt, Rachel and Lauinger, Tobias and McCoy, Damon},
  journal={Proceedings on Privacy Enhancing Technologies},
  volume={4},
  year={2025}
}
```

If you have any questions or feedback, please contact Cat Mai `cat.mai@nyu.edu`.