# Labeled Ads Dataset

## Instruction

The dataset is `labeled_ads.csv`. The codebook and labeling methodology is in `PETS25_codebook.pdf`.

The dataset contains 30,237 unique YouTube video ads. All rows are guaranteed to have non-null values for `preroll_ad_id`, `preroll_ad_video_url`, and `is_scam`. Other fields may contain nulls.

| Column Name              | Description                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------|
| `preroll_ad_id`          | A unique 11-character video identifier.                                                             |
| `preroll_ad_video_url`   | The full YouTube URL of the ad in the format `https://www.youtube.com/watch?v=PREROLL_AD_ID`.       |
| `preroll_ad_site`        | The landing domain that the ad directs to.                                                          |
| `preroll_ad_card`        | Text from the clickable overlay card shown during the pre-roll ad.                                  |
| `preroll_ad_advertiser`  | The advertiser's name as shown in the "About this advertiser" iframe.                               |
| `preroll_ad_topic`       | The topic category of the ad, collected via the "About this advertiser" iframe.                     |
| `preroll_ad_location`    | The advertiser's registered location, collected via the "About this advertiser" iframe.             |
| `tag`                    | Topic category label assigned during manual annotation (e.g., "Games", "News").                     |
| `is_scam`                | Binary label indicating whether the ad is predatory (`1`) or not (`0`), based on manual annotation. |
| `Notes`                  | Additional comments or reasoning for the assigned label.                                            |

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