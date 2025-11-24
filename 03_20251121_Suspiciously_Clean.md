![Suspiciously clean](assets/suspicious.jpg)

# The Suspiciously Clean Room

Reviewing a junior engineer’s code used to be like walking into a teenager’s bedroom.

You knew exactly where the mess would be. There were syntax errors heaped in the corner, a memory leak under the bed, and spaghetti code in the closet. It was messy but it was honest. You could look at the disarray around you and call out specific issues like, "Hey, you forgot to await that async call," or "You're not using the new array from this map; just use a for loop."

The teaching moments used to really jump out at you. They stared you in the face, usually in the form of code that never could have compiled in the first place.

But lately, something unsettling has happened. I open a pull request from a junior developer, and the room is… spotless.

The bed is made with military precision. The floor is vacuumed. The variable names are poetic. And the error handling uses a system so clever that I literally learn new things by reading it.

It's horrifying'.

## The Editor with No Typos
We are living through a weird era for technical leaders that feels a lot like being a newspaper editor after the invention of the perfect spellchecker.

In the past, my value as a senior leader was often found in the low-hanging fruit; especially when it came to juniors. I was the grammar police. I caught the typos. I pointed out the run-on sentences. But now? The AI handles the grammar. The AI handles the syntax. The code that lands on my desk is syntactically perfect.

Whenever I read a PR lately I hear that quote from Office Space: "So what would you say you *do* here?

When the "spelling errors" evaporate, we have to stop looking at the words and start looking at the story. We have to shift our perspective from syntax to semantics, and deeper still, to intent.

Since I can no longer critique the fact that a junior dev forgot to handle a null promise, I’ve found myself looking for more subtle signs of struggle, and oddly, signs of too little struggle.

## The Homogeneity Test
Because the AI is so good at writing generic, isolated blocks of code, the new struggle isn't "does this work?" It's "does this fit?"

My code reviews have shifted almost entirely to homogeneity of design.

AI is trained on the entire internet. It writes great code, but it also writes average code. It doesn't know that in this specific project, we handle state management in a weird, idiosyncratic way because of a legacy decision made three years ago. It doesn't know the subtle architectural patterns we’ve established to keep our sanity.

Now, when I look at a PR, I’m not really looking for bugs anymore (that was one hell of a habit to break). I’m looking for aliens. I’m looking for code that is technically correct but culturally wrong for our codebase. I’m looking to see if the junior engineer just pasted the solution, or if they molded it to fit the neighborhood.

## The Blind Man’s Hearing
There is a secondary effect to this "perfect code" phenomenon that I didn't see coming. Reminds me of the old adage about how when you go blind, your hearing sharpens to compensate.

Because there is so much less to criticize on the technical side, my "managerial hearing" has become hypersensitive to soft skills.

I’ve realized that in a world where anyone can generate working code, the differentiator is no longer who can code the fastest, but who is most curious about what we're doing.

I have noticed a stark divide forming in the junior ranks:

### The Silent Shippers: 
These developers are satisfied to let the machine do the heavy lifting. They crank out the ticket, the TS compiler doesn't complain, and they push it. They never call. They never message. They are terrifyingly quiet because they aren't struggling, which means they aren't learning. They are passengers in a self-driving car.

### The Noise Makers: 
These are the developers who will succeed. They pull me aside. They DM me at 2 PM on a Tuesday to ask, "Hey, Copilot suggested this pattern, but it feels like it conflicts with how we did the User module. What do you think?"

The "Noise Makers" are exhibiting the desire to do something other than just have the AI do the work. They are searching for the why.

## The New Hallmark of Talent
Poor developers hide behind the competence of the AI. They use it as a mask to cover their lack of understanding. They treat the job as a transactional exchange of tickets for code, with the AI as the middleman.

But the great developers? They treat the AI like a hyper-competent intern. They use it to speed up the boring stuff, but they are constantly checking its work, questioning its architectural decisions, and (most importantly) asking me how to bridge the gap between the AI’s logic and our business’s reality.

As technical leaders, we need to stop congratulating ourselves for catching syntax errors. That game is over. We need to lean in to our support for the engineers who are trying to evolve alongside the assistance.

We aren't looking for people who can write perfect code anymore. We have machines for that. We're looking for people who know when the perfect code is wrong.