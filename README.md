# Day 2
## Guide to create git and github connection with ssh key
### SSH key
- Generate an SSH key using:
```
ssh-keygen -t rsa -b 4096 -C "your_email@email.com"
```
- copy the ssh key from localhost with 
```
cd ~/.ssh
cat id_rsa.pub
```
- paste the public key on your github in settings GPH SSH key option in 
your profile menu and create key

### Repos
- go back to your terminal after creating key
- go to the folder in which you want to initialise your repository
- initialise repo using:
```
git init
```
- to create a new file use:
```
touch filename
```
- add your file(s)
```
git add filename
or
git add . // adds all files in the folder to the repo
```
- edit file
```
nano filename
// save and exit using CTRL+X, then y
```
- run the following github commands: 
```
git commit -m "msg"
git branch -M main
git remote add origin git@github.com:USER_NAME/Repo_name.git
git push -u origin main
```
- for all subsequent edits to the same files, you need to:
```
git add . // add the files
git commit -m "msg" // commit the changes
git push -u origin main // push to origin
```
- go back to github repo to verify the changes and connections


## Business skills
### Time and Tasks management
- Time management is "the range of skills, tools and techniques utilised 
to accomplish specific tasks, projects and goals"
- Task management is "the process of managing a task during its 
lifecycle, including planning, tracking and reporting"
- some T&T management tools include: Outlook calendar, Trello, a diary 
planner etc. Effectively anything that allows you to organise how time 
is distributed across tasks
- Pareto principle: 80% of the consequences come 20% of the causes. Not 
all features have the same impact on the final product so it's important 
to prioritise
- Eisenhower principle: prioritise tasks based on whether they're 
important and/or urgent
```
1. Important and Urgent - Do immediately
2. Important but not Urgent - Decide the appropriate time to do
3. Urgent but not Important - Delegate to someone else if possible
4. Neither Important nor Urgent - Delete from plans (waste of time)
```
- how to prioritise tasks:
```
- Necessary things are urgent and important
- Quality is important but not urgent
- Deception is urgent but not important
- Waste is neither
- use Two minutes rule
```

### Communication
- communication is essential to the functioning of a business. Problems 
in communication can lead to:
```
- potential loss of bussiness (clients, projects etc.)
- discord and conflict between members of the organisation
- lack of coordination resulting in an unsuccessful project
```
- it's important to listen to others and be open to criticism
 also important to be constructive in one's criticism and not simply 
negative
- we all have cognitive biases which can hinder our ability to make 
well-informed, objective judgments. some examples:
```
- Anchoring
- Confirmation bias
- Bandwagon bias
- Authority bias
```
- to minimise the influence of cognitive biases, we should seek to be 
self-aware so that we can detect faulty assumptions in our reasoning
- 6 coloured hats:
```
- White hat: focus on the relevant factual information
- Yellow hat: think optimistically, looking at the benefits/positives
- Black hat: think critically, looking for risks and problems
- Red hat: express intuitions and feelings you have about the issue
- Green hat: think creatively, outside the box, for different 
possibilities and ideas
- Blue hat: ensure that the guidelines for the 6 hats are followed in a 
well-balanced manner
```
### Dealing with conflict
- conflict occurs when opposing viewpoints clash. This can lead to 
problems unless effectievly handled.
- it's important that each side of the conflict makes an effort to 
understand the disagreement and the opposing viewpoint
- communication is key. Ask others for their perspective to help you 
understand why they disagree. Listen well and attentively
- be willing to compromise in order to reach common ground and reconcile
- conflict often occurs as a result of different personalities
- some personality traits to keep in mind:
```
- Extroverts
- Introverts
- Supporter
- Director
- Analytical
```
- understanding the personality of individuals in important for 
understanding why the think/behave the way they do, and decide how best 
to approach them
