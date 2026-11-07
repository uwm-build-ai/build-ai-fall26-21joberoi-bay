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
- { as_a: "", headline: "", i_want: "", so_that: "", value_why: "", tech_note: "" }
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