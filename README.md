# Instagram-Posts-Engagement-Analysis-Natural-Language-Processing
Engagement analysis of the Instagram posts for National Geography using image labels and captions


## Objective:

Analyze the National Geography page on instagram to understand

- What type of posts are engaging? - Engagement Analysis
- What are the major topics for these posts? - Topic Analysis
- Which topics are the most and least engaging?


## Data Source:

Data is scraped from the following instagram page:
https://www.instagram.com/natgeo/?hl=en


## Analysis Steps:

- Scrape the image urls, likes and captions from National Geography instagram page
- Use google API to extract the image labels
- Create an engagement scores by taking weighted average of likes and comments for the posts
- Based on the engagement score (high or low), build logistic regression based on caption, image labels, and the combination of both
- Topic modeling - Identify topics for the posts based on word distribution
- Identify the topics for top and bottom quartile


## Findings and Recommendations:

Based on LDA, we can see that many of our posts fall under the main category of nature. There are many overlaps within these topics, given that most are related to nature, landscapes and animals. People expect these photos from NatGeo, and these photos are probably the reason they are actively following the account. NatGeo is first and foremost known for their nature based magazines, which have been a household name since 1888. The Instagram account is an extension of this brand image they have created in homes, and thus, it is essential to maintain that on different platforms as well. However, there is also room to engage with a new userbase through Instagram, which is why we recommend slowly starting to add in a mix of new images corresponding to other topics.

Looking at just our high engagement posts, we see that three topics stand out with the highest scores. These topics include Photography, Nature, and Mountainous terrain. We can assume that users on Instagram are generally more likely to be interested in taking good photos – they are, after all, browsing the social media platform to see images! So NatGeo can group these together by finding new perspectives in photographing nature and mountains. People are also interested in images of nature probably because it is a respite from their day to day; thus, we can perhaps look to optimize our posts to encourage high engagement by posting at certain times of the workday when people tend to find their days dragging (for example, at 2pm when the post lunch coma hits).

Our low engagement posts surprisingly coincide with topics that National Geographic post the most about. They are posting many photos about the natural environment, yet they aren’t receiving the engagement they want on these pictures. This could be because people’s Instagram feeds are oversaturated by these images. Posts with more rugged terrain tend to be less popular, possibly because it appeals to a different type of beauty. We would suggest focusing more on posting images that develop engagement, like those listed under high engagement, and reduce the number of nature posts to a maximum limit per week. Limiting the saturation of these images on people’s feeds might encourage more engagement with the posts of nature in general.

One thing that could be useful to monitor is how the trends in engagement topics change based on season. For example, more individuals might engage with travel related images prior to planning a trip, which would cause an increase in certain topic label engagement. They may also want to see more images of people/human elements of emotion during the holidays, and pictures of sunny warm places in the winter. Looking at how engagement changes by season in general could be a great way to drive engagement by posting more targeted images at certain times of the year.
