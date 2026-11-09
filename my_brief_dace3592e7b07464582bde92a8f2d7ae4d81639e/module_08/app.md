# 🧠 Study Buddy

````
### 🎯 Problem

[My choice](welcome.md)
{: .import bench="true" }

**{= my_project.first.name }** — {= my_project.first.story.replace(my_project.first.character, persona.name or my_project.first.character) }

```yaml
name: Lina
role: Second-year psychology student balancing Statistics 101 with other required courses.
goal: Earn at least a B+ in Statistics 101 this semester.
frustrations:
  - Runs out of study time after spending three hours on one statistics exercise, leaving her other assignments unfinished.
quote: Three hours on this one question, and I still have other homework. Can someone help me see where I went wrong?
says:
  - Is anyone who passed statistics available tonight?
thinks:
  - I keep trying, but I still don't understand what I'm doing wrong.
does:
  - Rereads her notes, watches tutorial videos, and asks classmates for help.
feels:
  - Frustrated, tired, and worried about falling behind.
```
{: .persona #persona save="zim.yaml" }

```yaml
need: Wants to earn at least a B+ in Statistics 101 this semester
product: Study Buddy
category: Free peer tutoring app
benefit: Aims to save Lina 2 hours of study time per week by connecting her with an available student who passed Statistics 101
alternative: Searching class group chats and watching unrelated tutorial videos
difference: Uses AI to identify the topic in her question and rank peers by relevant course experience and current availability, while Lina chooses whom to contact
market: "College students spend an average of $45 per semester on ad‑hoc tutoring or study‑group services (verified, Statista 2023)."
```
{: .pitch #pitch save="pitch.yaml" persona="persona" }

### 🗺️ Map and backlog

[My map](#)
{: .runner src="map.md" bench="true" title="" }

```yaml
- as_a: Lina
  headline: Help Request Submission
  i_want: Submit a help request with my statistics exercise, course, and available times.
  so_that: I can ask for help as soon as I get stuck.
  business_value: 85
  value_why: Lets students ask for help sooner and saves study time.
  tech_note: Use a structured form and check for scheduling conflicts.

- as_a: Lina
  headline: AI Buddy Matching
  i_want: "🤖 Get buddy suggestions based on my question, course, and availability."
  so_that: I can find a relevant peer without searching class chats.
  business_value: 65
  value_why: Speeds up the search, though incorrect topic matches can reduce trust.
  tech_note: Use an existing model to identify the topic and let Lina correct the tag.

- as_a: Lina
  headline: Select Buddy Interaction
  i_want: "👤 Choose whom to contact and see whether they accept or decline."
  so_that: I can arrange a session with a willing buddy.
  business_value: 70
  value_why: Confirms that the buddy can help and reduces scheduling delays.
  tech_note: Show pending, accepted, or declined status to both students.

- as_a: Lina
  headline: Practice Quiz Feedback
  i_want: Take a short practice quiz with feedback after the session.
  so_that: I can check my understanding and ask a focused follow-up.
  business_value: 55
  value_why: Reinforces learning, though a small question bank can get repetitive.
  tech_note: Start with a small bank of reviewed questions and explanations.
```
{: .dataset #backlog }

```csv
my features, read from my space
```
{: .datagrid source="backlog" save="features.yaml" columns="headline, i_want, business_value, value_why, tech_note" height="260" title="📋 My features" }

### 🙋 Author

[My CV](#)
{: .runner src="../module_01/cv.md" bench="true" }
````
{: .tabs #menu }