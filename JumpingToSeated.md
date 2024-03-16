# How to Jump Through to Seated Position in Ashtanga Yoga

This describes how to jump your legs through your arms from Downward Facing Dog to seated position, a frequent maneuver in Ashtanga Yoga.

There are two main methods:

A. Low hips, straight legs

B. High hips, folded legs.

## Prerequisites
To perform either method successfully, you must have sufficient hamstring flexibility, and hip, abdominal/core, and shoulder strength to connect your upper thighs with your lower belly, unite them, and arc that unit through a portal essentially as long as your arms and as wide as your shoulders. Here are a few tests to see if you meet those prerequisites:


1. From standing, fold forward to the extent that you can touch your chest to your thighs, fairly tightly.  You want to be like a hair pin. This requires hamstring/back-body flexibility and hip flexor contraction.
2. From seated, press your hands into the floor by your hips, and lift your self (or butt, at a min) up off the ground using the strength of your shoulders and core. Try it with straight legs and sitting on your shins. Notice that you also have to contract your abdominals and hip flexors, and protract your shoulders to clear the floor.    

## Starting position: The Crouch and Spring 
The starting position for both methods A and B is the same: the crouch and spring.

From Downward Facing Dog, come into a crouch position. Push your chest toward your thighs while bending your knees, keeping your butt low and allowing your heels to come up as you push through the balls of your feet. Your tailbone is tucked.  The balls of your feet are pushing you foward, while your hands, arms, shoulders are pushing you backward, like coiled, wound spring.

## Method A: Low hips, straight legs
TIP: For this method, before you get into the crouch position, place a blanket between your thighs and belly. Don't let it slip out the entire time.

From the crouch position, do the following:

1. Look forward.  See where you're going.  Keep looking there.

2. Release your coil, pushing off your feet, straightening your legs, letting your hips arc up a bit. Quickly execute the next step.

3. At the top of your arc, with those hip tucked, quickly close the legs to the chest and let momentum shoot your feet through your arms.

4. Lead with your feet but steer with your hips, using your core to drive your hips and legs forward and through the arms. 

## Method B: High hips, folded legs

From the crouch position, do the following:

1. Spring your hips up in an arcing path until they are directly over your shoulders.

2. At the top of the arc, fold your legs, cross your shins and tuck them close your body until they are a unit.

3. Arc your belly-leg compact unit under and forward, through your arms.
 

# Exercise 12: Merging Branches
For this exercise, you will create branches and merge them back into master, first with no conflict, and then with a conflict to resolve. Unlike previous exercises, I will not give you exact instructions. It is up to you to figure out how to do the steps.

## Merge without conflict
1. In your terminal console, create a new branch and switch to it. You get to choose the name.
2. In your editor, make a change to one or more lines in docs.md, but not all of them.
3. In the terminal console, add, commit, and push. Remember that git push origin will fail, but will return the full command you need to create a branch on GitHub and upload the changes.
4. Change to the master branch.
5. In your editor, note that your changes are no longer there. Make one or more changes to lines that you did not change in your branch. In other words, your branch should have changed certain lines, but the master branch should change different lines.
6. In the terminal console, add, commit, and push.
7. Open up GitHub in your browser. Verify that you can switch branches, and you can see the appropriate differences in the master branch and your new branch.
8. Click on the exercise link to return to the top level of the repository.
9. Create a merge request from your new branch into master by clicking New pull request.
10. Leave the base as master, but change the compare to your new branch so that it shows:

master  new branch

11. Add a description in the Write tab.
12. Click Create pull request. You should see a message that there are no conflicts, since you did not make changes in the two different branches to the same line.
13. Click on Files changed near the top to review the changes.
14. Click on Review changes and add a comment to a change. Click Submit review to submit.
15. Click on Conversation near the top to get back to the pull request page.
16. Everything looks good, so click on Merge pull request to start the merge.
17. Click Confirm merge to make it happen.
18. If successful, click Delete branch to remove it from GitHub.
19. Return to your terminal console. If you aren’t already in the master branch, move to it.
20. Do a git pull to bring in the changes.
21. Go to your editor and verify that you are now seeing the changes from both the master branch and the new branch.
22. Finally, delete your new branch locally using git branch -d branch-name where branch-name is the name of the branch you created.
