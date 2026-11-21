# 👋 Welcome to my app

```sql
SELECT * FROM projects WHERE id = 'study_buddy'
```
{: .query bind="projects" #my_project }

**{= my_project.first.name }** — {= my_project.first.story }

I chose this project because I know how frustrating it is to get stuck on an assignment, and I want to make it easier for students to find someone who can help.

My aim: Social impact — help students who cannot afford private tutoring find free support from students who have already passed the same course.

My twist: Start with students at my school who need help with statistics. Students offering help must have passed the course,
and each request must identify the topic and when help is needed.