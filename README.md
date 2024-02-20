# Social-Media-Analysis
Enhance the engagement and performance of a gaming company social media platforms through data-driven strategies.

Key Challenges & Goals:
Engagement Analysis: Uncover typical engagement rates and explore the feasibility of a 15% target.
Posting Schedules: Determine the influence of posting times on engagement.
Game Performance: Assess the social impact of different game titles.
Media Efficacy: Identify the best-performing media type.
Campaign Evaluation: Pinpoint the top-performing campaign.
Strategy Formulation: Develop a tailored posting strategy based on insights.
Platform Expansion: Recommend strategies for expanding social media presence.

# Knowing Our Audience 
## Young Professional 

Age Range: 20s to early 30s
Gender: Predominantly Male
Location: North America

Characteristics: 
- Maintains a strong interest in games and esports while managing a professional career
- Comfortable with digital platforms, often use it for work & leisure 
- Have disposable income to invest in gaming equipment and merchandise 
- Looks for well-produced and informative content

## Teenager

Age Range: 13 to 19
Gender: Predominantly Male
Location: North America

Characteristics: 
- Devotes a significant amount of time to playing video games and/or following esports
- Strong emotional attachment to their favorite teams and players 
- Relies on parents to purchase merchandise and events tickets
- Enjoys discussing and sharing gaming-related content with peers

## Emerging Female Gamer 

Age Range: teens to early 30s
Gender: Female 
Location: North America

Characteristics: 
- Increasing interest and participation in esports and gaming communities
- Comfortable with digital platforms, often use it for work, school, & leisure 
- Older gamers may have disposable income to invest in gaming equipment and merchandise 
- Enjoys community-building, inclusive, and diverse gaming content

# Data Cleaning 
Prior to the data analysis, a critical step is to ensure the data's cleanliness and relevance. Here's the summary of our data cleaning process:

- Removal of Incomplete Observations: Eliminated 2 records with missing values in 'Published Date', 'Account', 'Account Type', and 'Media Type' fields

- Removal of Zero-Value Observations: Discarded entries with zero 'Total Impressions' and 'Total Engagements’

- Removal of Media Type “Album”: This media type consisted of only 1 record that had an engagement rate of 40%, skewing the findings.

# INSIGHTS 
## Engagement Rate by Account Type 
Our analysis reveals considerable differences in engagement rates when we break it down by account types.
The standout platform is Facebook (FBPAGE) with an engagement rate of 17.81%, significantly outperforming other account types which have engagement rates varying between 1% and 6%.

Potential Reason for High Engagement
Facebook's exceptional engagement rate can be traced back to multiple factors, including the platform's nature, user base, or our unique strategies implemented here.
Facebook's algorithm might favor posts from pages that users interact with frequently, enhancing visibility and, in turn, boosting engagement.
Alternatively, this could indicate that our content particularly resonates with the Facebook audience, or we've successfully harnessed Facebook's tools and features to optimize engagement.

Insights on Target Users:

Young Professional 
These audiences may exhibit increased engagement on platforms like LinkedIn due to its professional focus and Twitter for real-time esports updates and discussions.
Despite LinkedIn's average engagement rate appearing low, it could be worth exploring tailored content strategies for this group

Teenager 
This demographic likely displays higher engagement on youth-popular platforms like TikTok, Instagram, and YouTube, known for their video content.
Although Instagram shows a lower engagement rate currently, reassessing our strategy to better reach and engage this group could lead to more promising results.

Emerging Female Gamers
As a rapidly growing demographic in esports, female gamers are increasingly engaging with content that promotes inclusivity and representation in gaming. Platforms like YouTube, known for live streaming and diverse content, may serve as ideal channels to engage this audience.
A content strategy specifically tailored for this demographic could be beneficial, such as highlighting successful women in esports or creating content around inclusive gaming communities.

## Evaluating Engagement: Media Type Matters
- Carousel content, despite its potential for visual appeal and storytelling, has a relatively low engagement rate (4.07%), indicating that the current strategy for this format might need improvement.
- Link content has the lowest engagement rate (0.97%), suggesting a lower interest in outbound content or potential issues with the relevancy or appeal of the linked content.
- Text content surprisingly has a higher engagement rate (7.93%) than some visual formats (Carousel, Video), indicating that written content, when used effectively, can still engage the audience.
Potential Reasons
The low engagement rate for carousel posts might suggest a lack of compelling narratives within these posts, or possible user fatigue with swiping through multiple images or videos.
The low engagement rate for link posts suggests these may not be providing sufficient value to the audience, or the relevancy and appeal of the linked content may need to be reviewed.
The relatively high engagement rate for text posts suggests that quality written content, perhaps due to its ability to provide detailed insights or evoke emotional responses, can still be effective at engaging the audience.

User Analysis: 
Young Professional
- Given their professional focus, this group may find value in Link content that directs them to in-depth articles, tutorials, or resources related to esports, despite the overall lower engagement rate (0.97%) of Link content.
- Given their likely busy schedules, this group might appreciate easily digestible content such as Photos (9.07%) or Videos (8.11%), which can deliver impactful messages quickly.
- As professionals, they might appreciate Text content (7.93%) that provides deeper insights or thoughtful commentary on esports trends and developments.

Teenager
- With a pronounced preference for video content, teenagers might largely be driving the engagement rates for Videos (8.11%).
- They might also contribute to the engagement of Text (7.93%), engaging in discussions or commenting on posts about games, players, or esports events.
- This pattern aligns with engagement rates by account type. Platforms popular with this age group, like TikTok and YouTube, are renowned for their video content.

Emerging Female Gamer
- Attracted to Photo (9.07%) and Video (8.11%) content that highlights the experiences of female gamers or offers tutorials, game strategies, or reviews from a female perspective, they could significantly contribute to engagement rates.
- Despite the overall lower engagement rate of Link content (0.97%), they might also be responsive to Links that lead to female-centric gaming forums, articles, or resources.

## Day & Time of Day Effects on Engagement Rates 
- Tuesdays at 5 AM exhibit the highest engagement rate (0.51). Users may be interacting with content posted during off-peak hours, catching up with updates they missed while sleeping. Also, this time might coincide with peak activity times in other time zones. Thus, content catering to audiences in different US time zones or providing early-morning updates might be particularly effective at this time.

- Sundays at 8 PM and Thursdays at 9 PM have high engagement rates (0.29 and 0.21 respectively). These are typical leisure times, when users might be relaxing with social media after dinner or before bedtime. Posts that cater to casual browsing, such as lighter, entertaining content or recaps of the day's events, might perform well during these hours.

- Traditional high-activity times like Friday evening (0.16) and Sunday afternoon (0.13) see lower engagement rates in our data. This suggests a "noise" factor at play, where the higher volume of posts during these popular social media times could be making it harder for individual posts to stand out. Carefully timed or highly engaging content may be required to cut through this noise.

- Early morning hours on Wednesday and Thursday (7 AM with 0.21 and 0.20 respectively) show high engagement rates. Users may be checking social media as they start their day, and content offering a positive start to the day or essential updates could be particularly effective.

- The engagement rates significantly vary across different days of the week, pointing to a crucial relationship between content timing and audience routines. Notably, Thursday, Tuesday, and Friday emerge as the days with the highest engagement.
The higher engagement on these days could be attributed to the weekly rhythms of our target demographics. For example, users might engage more on Tuesdays (22.19%) after settling into the workweek, and on Fridays (19.50%) as they gear up for the weekend.

User Analysis: 
- Young Professional:
This demographics might show heightened engagement during their off-work hours, early mornings, lunch breaks, and evenings. This explains the high engagement rates seen on Tuesday at 5 AM (0.52), and Thursday at 9 PM (0.22).
Given their familiarity with digital platforms, they might use leisure time or breaks in their day to engage with content. Postings during these hours, especially on LinkedIn or Twitter, may see improved engagement.

- Teenager:
With school commitments, teenagers may show more activity on social media platforms outside school hours, typically afternoons and evenings. This reflects in the high engagement rate seen on Sunday at 8 PM (0.29).
There may be brief engagement periods early in the morning before school or during school breaks. However, these times may vary due to differing school schedules.

- Emerging Female Gamer:
Like teenagers, young female gamers might exhibit higher engagement during off-school or off-work hours. Strategic content posting during these high activity periods, specifically tailored towards this audience, could increase engagement.
The high engagement rate seen on Tuesday mornings (0.52) and Thursday evenings at 9 PM (0.22) could be leveraged by strategically posting content that resonates with this audience. This might include updates on popular female-led esports events, female-centric gaming initiatives, or game updates.

# Recommendations
## Strategies for Young Professionals 
- LinkedIn: Utilize this platform to target young professionals given its average engagement rate of 1.98%. It's best suited for more professional, in-depth content such as industry updates, career opportunities in the gaming field, or profiles of successful people in the esports world.

- Twitter: Use Twitter to provide up-to-date news and discussions about games and esports considering it has a decent engagement rate of 3.10%. Implement scheduled daily posts during the evening when they are most likely to be active online.

- Facebook: Leverage Facebook's high engagement rate 17.81% to share well-produced and informative content, such as high-quality photos or game highlights.

- YouTube: This platform is an excellent place to host more detailed, informative content with an average engagement rate of 4.33%. You could host expert game analyses, deep-dives into gaming strategies, or discussions about esports trends.

- Content Strategy: Focus on ''Mixed' content which had the highest engagement rates of 7.39%. This would serve the Young Professional's interest in well-produced, informative content.

- Timing: Post the content when the target users are more active, in this case it will be in the morning when they are on a breaks in their workday or during their commute. Also, in the evening where they are done with their workday. 

## Strategies for Teenagers
- TikTok: Use this platform to engage teenagers given the average engagement rate of 5.48%. Content here should be fun, engaging, and follow popular trends or challenges that align with gaming themes.

- Instagram: Despite a relatively low engagement rate of 2.35%, it's still popular with teenagers. Use this platform for visually appealing content, behind-the-scenes peeks, and posts that facilitate interaction like polls or questions.

- YouTube: Post game walkthroughs, tips and tricks, and other video content that teenagers can learn from and share. YouTube has an engagement rate of 4.33%.

- Twitter: Keep up the engagement with this group by tweeting about the latest esports news, game updates, and tweets that promote discussion and sharing.

- Content Strategy: The 'Video' media type has an engagement rate of 8.11% and is likely to resonate with this audience given their interest in visually engaging, immersive content. Prioritize creating videos that are entertaining, relatable, and sharable.

- Timing: Post the content when the target users are more active, in this case it will be in the afternoon to evening since they are out of school.

## Strategies for Emerging Female Gamers 
- Twitter: Use this platform to host open discussions and share the latest news, achievements, and challenges for female gamers, considering its higher engagement rate of 2.28% for Text posts.

- Instagram: Given its popularity among this demographic and an engagement rate of 2.89% for Photo posts, this platform can be utilized for highlighting successful female gamers and teams. Share behind-the-scenes looks at female esports players, and posts that facilitate interaction.

- YouTube: Post interviews with female gamers, game reviews, walkthroughs, and highlights that these gamers can learn from and share. YouTube has an average engagement rate of 4.33% for Video posts.

- LinkedIn: Though not traditionally a gaming platform, use LinkedIn to share professional insights about the industry and promote female-only tournaments and events. This could further the conversations around inclusion in the gaming industry.

- Content Strategy: The “Video” media type has an engagement rate of 8.11% and is likely to resonate with this audience given their interest in engaging, immersive content. Prioritize creating videos that are inspiring, informative, and relatable to their experiences.

- Timing: Given the data, this might be early morning, lunchtime, or late evening, depending on their personal and professional commitments.
