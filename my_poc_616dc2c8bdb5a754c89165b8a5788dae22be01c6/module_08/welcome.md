# 👋 Welcome to my app

```sql
SELECT * FROM projects WHERE id = 'study_buddy'
```
{: .query bind="projects" #my_project }

**{= my_project.first.name }** — {= my_project.first.story }

I chose this project because I have been stuck on homework late at night, and I know how much easier it is when someone who already passed the course can help.

My aim: social impact, helping students at my university get unstuck faster.

My twist: it is built for my campus in Milwaukee, so students find classmates who took the same course there.