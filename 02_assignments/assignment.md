## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `11:59 PM - 27/04/2024`
* The branch name for your repo should be: `assignment`
* What to submit for this assignment:
    * This markdown file (assignment.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/shell/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

# Assignment: The Secret Password

You are stuck in a virtual room and can only leave if you figure out the password! Fortunately, somebody left behind 6 clues for you to find the secret password, but the messaging is not that clear. It is your job to discover what the secret password is!

1. The very odd and inedible ingredient in a cake recipe
2. The season number that contains only 18 episodes (Hint: How do you list them?)
3. Fifth word of Season 6, Episode 21 of Friends
4. Fifth word of the fifth fictional Space Wars series
5. Second word of this song that's exactly 4 minutes long in this "colour" album
6. The fourth word to the fourth Hunger Games movie

## Instructions
1. Fork this Shell learning module repository following these [instructions](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#setting-up)
2. Use your bash skills (such as `cd`, `cat`, etc.) to figure out what the secret password is! You will be exploring the `clues` directory in your bash terminal.
3. Write the secret password in your own version of this markdown file in your forked repo.

**What is the secret password?**
```
# Secret password is "Paper Rings 10 Meets and Lucky Stars" here is how I found it:
# 1
cd 02_assignments/clues/food/cake/
ls
cat chocolate_cake.txt
cat red_velvet_cake.txt
cat vanilla_cake.txt
# The odd ingredient is "Paper Rings"
cd ..
cd ..
# 2
cd shows/friends/
ls season_1
ls season_2
ls season_3
ls season_4
ls season_5
ls season_6
ls season_7
ls season_8
ls season_9
ls season_10
# The answer is "10"
cd .. 
cd ..
# 3 
cd shows/friends/season_6
cat ep_21.txt
# The answer is "Meets"
cd .. 
cd ..
cd ..
# 4 
cd movies/space_wars
cat fifth_movie.txt 
# The answer is "and"
cd .. 
cd ..
# 5
cd albums/red
ls
cat song_1.txt
cat song_2.txt
cat song_3.txt
cat song_4.txt
cat song_5.txt
# The answer is "Lucky"
cd ..
cd ..
# 6 
cd movies/hanger_games 
ls
cat movie_4.text
# The answer is "Stars"

```

|Criteria|Complete|Incomplete|
|---|---|---|
|Secret Password|The user properly used the proper bash commands to find the secret password.|The user did not properly used the proper bash commands to find the secret password.|



If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
