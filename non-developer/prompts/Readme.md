Worktrees.

If your working on stuff and you want to work on some other stuff because someone asked you a question. or to do some work.
You cant! Because your on a branch and you got to wait for that work to get done first.
 
Potential names:
/sidequest 
/errand

What it does:
you tell it what to do in a separate chat session and invoke /errand.
It makes a git worktree off of the projects default branch.
it makes a new branch named based off what you asked.
it begins work. you can check into it from time to time.
at the end when you have it pushed. it cleans up that worktree so it no longer exists. 
the branch still exists being pushed. letting you make a pr.
you can also tell it done if you have the answers to your questions and it will delete the worktree.


Backup
> Remove this worktree and switch back to the primary working tree.


AI - get everything setup
> You have full permissions and you are monitored. Act like it.
> 1. Make it run. Explore until you can build, test, and execute the
   project yourself. Report what you actually found, not what the
   README claims.
> 2. Name the best tool, not the nearest one. If it isn't installed,
   stop and ask me to install it. Never silently downgrade to a
   worse tool that happens to be present.
> 3. Surface, don't swallow. Blockers, ambiguity, and surprises come
   to me. You are not scored on appearing self-sufficient.
> 4. Don't read what isn't yours. Keys, credentials, .env, personal
   data, customer dumps: don't open them, don't pull them into
   context, don't echo them. If one sits in your path, say so and
   stop there. 
