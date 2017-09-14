# lsanchez-web-developer
Repository for personal web site project

## Milestone 1 feedback

Your code is extremely readable and well indented; great job! If you're going to be working within a corporation or larger company your fellow coders will love you for your ability to organize your code. Your gitignore and directory structure look great. The only change you may want to consider is moving your index.php into your public_html directory.

You've done a great job targeting a general employer type that you're targeting, however, is there a specific sector you'd prefer to work within? Do you prefer a company that focuses on physical goods, software, manufacturing, etc? If not, that's totally fine. Your preferences will most likely change as time elapses and you become more familiar with web development.

Your persona section is overall very good, however, we want you to be more specific in regards to the technology being used. Does this hiring manager have an iPhone, Android, Windows or Blackberry (does blackberry still exist?...). 

Your HTML passed inspection by [W3 Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbootcamp-coders.cnm.edu%2F~lsanchezrees%2Flsanchez-web-developer%2Fpublic_html%2Fdocumentation%2Fmilestone-1.php), and overall you've done an excellent job with milestone 1! You pass with a [tier IV](https://bootcamp-coders.cnm.edu/projects/personal/rubric/). You're free to move on to [milestone 2a](https://bootcamp-coders.cnm.edu/projects/personal/milestone-two/).

## Milestone 2a Feedback:

### Feedback 
Good job on Milestone 2a. Your directory structure is correct. You only have a few errors in your HTML https://validator.w3.org/nu/?doc=https%3A%2F%2Fbootcamp-coders.cnm.edu%2F~lsanchezrees%2Flsanchez-web-developer%2Fpublic_html%2Fdocumentation%2Fmilestone-2.php. I also really like your content strategy, and it should work great for PWP. The wireframes look great and I like how simple and straight to the point they are. Feel free to start working on milestone 2b whenever you are ready. 

### Fixes
You did not submit your final changes on milestone 2a to github. Technically we only grade what is on github. If I were to do so I would have had to give you a Tier I since you have no wireframes, which would have been a shame. Since this your first offense I am going to let it slide, but please remember to commit and push before turning in assignments. 

### Grade Tier III

## Milestone 2b
Your Milestone 2b passes at [Tier IV](https://bootcamp-coders.cnm.edu/projects/personal/rubric/)

## PWP Milestone 3 Feedback
Beautiful work on your PWP. You've done a nice job with CSS getting this quadrant layout mobile friendly and looking nice! This can be tricky, and is something that requires a custom touch. There are a few minor quirks here and there that I'm seeing with the layout and code:

- There's a horizontal scrollbar across the bottom of the browser window, and that generally tells me there's a problem with the Bootstrap grid. Using DevTools I see where the problem lies - there is a `.row` outside of a `.container` - see line 190.
- It's inadvisable to use "hard-set" padding to size your form the way you have it, and it's not working well on mobile. A better way is to place your contact form inside a Bootstrap container and column instead, and remove that CSS rule on line 110.
- jQuery is loaded twice in your `<head>` tag - remove lines 41 and 42.
- Ideally, place your resume doc in an appropriate subdirectory.

You contact form appears to work correctly - check your email and see if you recieved my test message.

Overall nice work here. Your Milestone 3 passes at [Tier III](https://bootcamp-coders.cnm.edu/projects/personal/rubric/)

Your overall grade across all of your PWP Milestones is 31/40 points (77.5%).

- Milestone 1 - 20%: Tier III 30(0.2) = 6
- Milestone 2a - 20%: Tier III 30(0.2) = 6
- Milestone 2b - 10%: Tier IV 40(0.1) = 4
- Milestone 3 - 50%: Tier III 30(0.5) = 15

### Edits &amp; Suggestions
- We didn't get around to discussing _favicons_ - which are those little custom icons that appear in the browser tab next to the page title. Check out this tool that generates a comprehensive set of them that is cross-device compatible: https://realfavicongenerator.net/ 
