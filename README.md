# hacker-news

🔨 Hacker News
Hacker News is a social news website focusing on computer science and entrepreneurship. It is funded by the Y Combinator incubator. It’s a popular platform to get your daily dose of tech related stuff. You can check it out here: https://news.ycombinator.com/news
Your Mission
Build a version of Hacker News with a search feature by using their API: https://hn.algolia.com/api
How do I do that?
You want to display all the articles about a specific topic. Let’s say “React”. You’ll have to target the Search endpoint of the API:
Level 1
# Load mock news from a JSON file (json file here); or load news directly from the HN API about a pre-set topic (e.g: React) # When this is done and working, create a search bar, and allow the user to search for any topic (search input + “Search” button)
(Bonus) Level 2:
# Display a spinner or a loading message when the news are being fetched # Handle the scenario where no news match the user search # Handle potential errors from the API and alert the user
(Bonus) Level 3:
# Implement pagination
(Bonus) Level 4:
# Use a library of UI components to create your news site (such as React Semantic UI, Material UI, React Bootstrap, Reactstrap)
Note: You are only allowed to use functional components with hooks for this challenge 🙂
