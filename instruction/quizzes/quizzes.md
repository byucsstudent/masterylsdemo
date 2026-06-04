
# Interactions


![Topic Cover](https://raw.githubusercontent.com/csinstructiontemplate/emptycourse/refs/heads/main/cover.jpg)

```masteryls
{"id":"a3b2a9f8-25e3-4ca4-8cca-42f3eb20537d", "title":"Multiple choice", "type":"multiple-choice" }
A **multiple select** question can have multiple answers. Incorrect selections count against correct ones when calculating the correct percentage.
- [ ] This is **not** the right answer
- [ ] This is **not** the right answer
- [x] The right answer
- [ ] This is **not** the right answer
```


```masteryls
{"id":"a3b2a9f8-25e3-4ca4-8cca-42f3eb20537e", "title":"Multiple select", "type":"multiple-select" }
A **multiple select** question can have multiple answers. Incorrect selections count against correct ones when calculating the correct percentage.

- [ ] This is **not** the right answer
- [x] This is _the_ right answer
- [ ] This is **not** the right answer
- [x] Another right answer
- [ ] This is **not** the right answer
```


```masteryls
{"id":"b1de730b-9331-4e2f-8c7b-b8ff66a51a06", "title":"Teaching", "type":"teaching" }
Help me understand the **Socratic method**.
```

```masteryls
{"id":"af6b1470-6384-45f8-a13a-045b9278f6a3", "title":"Lesson Reflection", "type":"likert", "showResults":"always"}
Rate each statement on the same scale.

Scale: Strongly disagree | Disagree | Neutral | Agree | Strongly agree

| qid | item |
|-----|------|
| prep | I came prepared for class. |
| engage | I stayed engaged throughout the lesson. |
| confidence | I feel confident using the new skill. |
```

```masteryls
{"id":"b1de730b-9331-4e2f-8c7b-b8ff66a51a04", "title":"Prompt", "type":"prompt" }
Ask the learner to craft a prompt.
```

```masteryls
{"id":"b1de730b-9331-4e2f-8c7b-b8ff66a51a05", "title":"AI Web Page", "type":"ai-web-page", "allowAiPrompt":true, "height":"150px"}
Revise the starter HTML manually, then submit.

~~~html
<h1>hello</h1>
~~~
```

```masteryls
{"id":"b1de730b-9331-4e2f-8c7b-b8ff66a51a08", "title":"Web Page", "type":"web-page", "file":"instruction/topic1/starter-page.html", "height":"180px"}
<!DOCTYPE html><html lang="en">
<head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Welcome</title><style>
body { margin: 0; display: grid; place-items: center; min-height: 100vh; background: #232323; font-family: system-ui, -apple-system, sans-serif; color: #111; }
h1 { font-size: clamp(2rem, 8vw, 4.5rem); font-weight: 800; letter-spacing: -0.03em; text-align: center; background: linear-gradient(135deg, #6366f1 0%, #a855f7 50%, #ec4899 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; animation: reveal 1.2s cubic-bezier(0.16, 1, 0.3, 1); }
@keyframes reveal { from { opacity: 0; transform: translateY(20px); filter: blur(10px); } to { opacity: 1; transform: translateY(0); filter: blur(0); } }
</style></head>
<body>
<h1>Welcome curious learner</h1>
</body></html>
```


```masteryls
{"id":"ef1f9d20-99b5-4adc-ab98-3a6536234103", "title":"Team Pulse (Editor Results)", "type":"likert", "showResults":"editor", "required":"false"}
How are you feeling about the following.

**Note:** _Only an editor can see the results_

Scale: 😄|🙂|😐|🙁|😢

| id | statement |
|----|-----------|
| communication | My team communicated effectively this week. |
| support | I felt supported when I got stuck. |
| ownership | I took ownership of my assigned tasks. |
```

```masteryls
{"id":"40824056-92f3-48e6-8f68-f0f63d67071f", "title":"Multiple select survey", "type":"survey",  "multipleSelect": "true" }
What would you have as a pet?

- [ ] 🐱 Cat
- [ ] 🐶 Dog
- [ ] 🐹 Hamster
- [ ] 🐠 Fish
- [ ] 🪨 Rock
- [ ] Other
```

```masteryls
{"id":"bd56d044-03ce-45f2-b004-462c911ce27d",   "title":"Multiple choice survey", "type":"survey" }
I found this instruction helpful?

- [ ] 🙂 Helpful
- [ ] 😐 **Somewhat** helpful
- [ ] 🙁 **Not** helpful
```

```masteryls
{"id":"25a5068d-4b97-4c7d-9936-cf97b426f87e", "title":"Essay", "type":"essay" }
What is the **Fermi Paradox**?
```

```masteryls
{"id":"681edaf2-8c77-46cc-8014-f3ed1634b199", "title":"File submission", "type":"file-submission", "allowComment":true  }
Provide a screen capture of your testing results.
```

```masteryls
{"id":"76b87c04-6c7b-430e-9b04-aae522d571e2", "title":"URL submission", "type":"url-submission", "allowComment":true }
Provide the URL of your production website.
```
