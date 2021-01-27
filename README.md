## Overall Introduction
The HAN-mini dataset for news recommendation was collected from anonymized behavior logs of Green News website (http://news.bjfu.edu.cn/). As an important news website for external and internal publicity of Beijing Forestry University, Green News aims to report the latest developments and achievements of the university in a timely and accurate manner, including teaching and scientific research, academic exchanges, campus culture, forestry, and environmental science trends at home and abroad. We selected user logs from March 2019 to Aprial 2019 to construct the HAN-mini dataset, which is a part of our entire dataset. To protect user privacy, each user is de-linked from the production system when securely hashed into an anonymized ID. 

The datasets are intended for non-commercial research purposes only to promote advancement in the field of recommendation systems and related areas. If you have any questions, please feel free to contact us at dingqi@bjfu.edu.cn.

## Dataset Files

### news.txt
The news.txt file contains information of news. It has 3 columns divided by the tab symbol:

- news_id. The ID of a news.
- news_title. The title of a news.
- release_time. The release time of the news 


### visitlog.txt
The visitlog.txt file contains users' news click hostories. It has 5 columns divided by the tab symbol:

- user_id. The anonymous ID of a user.
- news_id. The ID of a news.
- visit_time. The time when the user clicks on the news.


### hot_news.txt

The hot_news.txt file contains information of hot news of March 2019 which are ordered by the number of clicks. It has 2 columns divided by the tab symbol:

- news_id. The ID of a news.
- news_title. The title of a news.
