# Super Bowl Ads

This folder contains the data behind the story [Hed TkTk](http://fivethirtyeight.com/) (link tktk).

Which ads are included in this data are based on lists from [superbowl-ads.com](https://superbowl-ads.com/). This data includes all ads from the 10 brands that advertised the most in Super Bowls from 2000-2020. Ads were then matched to videos from [YouTube](https://youtube.com). The criteria categories were rated by hand by FiveThirtyEight-ers.

Header | Definition
---|---------
`year` | Year the spot aired, according to superbowl-ads.com
`brand` | Brand of advertiser
`superbowl_ads_dot_com_url` | Link to superbowl-ads.com entry for this ad
`youtube_url` | Link to YouTube video matched to this ad
`funny` | **Was it trying to be funny?** Is the ad jokey, goofy, weird or silly? Funny commercials (or ones that are trying to be funny) are a clear 1 here. Anything serious or dramatic is a 0.
`show_product_quickly` | **Did it show the product right away?** Can you tell what is being advertised within the first 10 seconds of the commercial? If you can see the product or brand name on the screen, that counts.
`patriotic` | **Was it patriotic?** Did the commercial make a patriotic appeal, either clear or subtle? Any glimpses of an American flag or the words "America" or "United States" counted as patriotic, as did imagery of the armed forces, manufacturing and farming.
`celebrity` | **Did it feature a celebrity?** If we saw a celebrity we recognized, we checked this one off.
`danger` | **Did it involve danger?** Did we see any violence, threats of violence, injuries, fighting or guns? Any allusions to death or hokey injuries also counted here.
`animals` | **Did it include animals?** Did an animal show up at any point in the ad? Even one-frame appearances counted.
`use_sex` | **Did it use sex to sell its product?** We counted any subtle or overt suggestions of sex, sexuality, sex appeal or nudity.
