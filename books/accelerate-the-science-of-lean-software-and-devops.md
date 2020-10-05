# Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations

(2018)

By Nicole Forsgren PhD, Jez Humble and Gene Kim

## About the authors

### Nicole Forsgren 
[LinkedIn](https://www.linkedin.com/in/nicolefv/):

> I am the VP of Research & Strategy at GitHub and a technical founder/CEO with a successful exit to Google. I am also a member of ACM Queue's Editorial Board. In a previous life, I was a software engineer, sysadmin, professor, and hardware performance engineer. I have published several peer-reviewed journal papers and have been awarded public and private research grants (funders include NASA and the NSF), and my work has been featured in the Wall Street Journal, Forbes, ComputerWorld, and InfoWeek. 

### Jez Humble
[LinkedIn](https://www.linkedin.com/in/jez-humble/)

Software Reliability Engineer at Google CLoud.

### Gene Kim
[LinkedIn](https://www.linkedin.com/in/realgenekim/)

> Gene Kim is a multiple award-winning CTO, researcher, and co-author of The Phoenix Project, Beyond The Phoenix Project, The DevOps Handbook, and The Visible Ops Handbook. He is founder of IT Revolution, hosts the DevOps Enterprise Summit conferences, and speaks around the world. He lives in Portland, OR with his wife and children.

# Notes

The book is divided into 3 parts:
- Part 1: Summary of results of a 4-year survey by Google PhD researcher Nicole Forsgren
- Part 2: Explanation/defense of survey methodology
- Part 3: Married couple Steve and Karen Bell explain how they applied these lessons at ING Netherlands

**Part 1** is by far the most interesting and most useful and the one worth discussing below.

**Part 2** will likely be a tedious slog for most readers as it's a defense psychometric survey mumbo jumbo like “discriminant validity” and “latent constructs” that attempts to justify the validty of psychometry as a field and survey-taking as a measurement diagnostic. That honestly seems like a totally separate effort from evangelizing best practices for DevOps and perhaps its own essay or book.

**Part 3** where the Bells describe their experience adopting these practices at ING Netherlands is uninhibited twaddle. It alternates between Dilbert-style dialog (“ING underwent a significant shift to a multidimensional, matrixed structure organized along lines of business, enabling the continuous flow of customer value”, p. 183) and meaningless pablum (“Develop and maintain the right mindset”, p. 194) before ending with the exasperating warning “Don’t look to other enterprises to copy their methods and practices” (p. 194) to apparently render the entire chapter moot.

But back to **Part 1**, the 4-year survey, which has a lot of interesting ideas — some of which I agree with, some I do not. But worth examining.

## Best Practices Recommended by the Survey
1. Measure outcomes over outputs; lines of code, Jira tickets, or Story point velocity are ultimately meaningless (p. 13)
1. Full utilization doesn’t account for unknown unknowns or emergencies and will slow your team down, so bake in slack time (p. 13)
1. Frequent deployments increase stability and decrease risk (p. 17)
1. If a system is strategically important to the business, build it internally so you can have full control. If not (e.g. HR systems), go with a vendor (p. 26)
1. Reliable systems don’t require a lot of other systems to function (p. 62) and decrease the overall level of bureaucracy needed to operate
1. Use a prebuilt security toolchain that devs can integrate concurrently with feature development instead of painfully trying to bolt in security requirements later (p. 67)
1. Utilize visualization techniques for in-flight work to help deliver fewer things faster (p. 77)
1. Carve out explicit time for tech debt and cross-team experimentation (p. 123) as well as trying new tools
1. Practice simulating outages (p. 125) and make monitoring a priority (p. 127)
1. Managers profit by asking questions of empathy (“Help me understand the problems you’re encountering”) vs questions of delivery (“Why isn’t this done yet?“) (p. 187)

I think all of the above is useful and worth meditating on in its own right.

Many things I disagreed with, however.

## Made-up Nonsense
1. Forsgren attempts to break down corporate culture into 3 levels (“basic assumptions”, “values” and “artifacts”)  (p. 29) - you can slice and dice human groupings into countless structures, these 3 buckets don’t really shed light on much
1. Forsgren relies on a “topology” of corp cultures developed in 1988 by sociologist Ron Westrum: “pathological” aka fear-based, “bureaucratic” and “generative” (p. 34) - the ‘good’ kind; and unironically asserts that the “Westrum construct is both valid and reliable”
1. The “Rugged Movement Manifesto”, which includes vows like “I am rugged because I assure my code will support its mission” (p. 73) conveys no actual meaning while managing to sound like a blood oath for joining a cult
1. Forsgren asserts that devs work better when choosing their own tools but contradicts herself a few pages later saying “there is a place for standardization” (p. 66)
1. Forsgren claims good leadership is about “vision”, “communication”, “stimulation” and “recognition” (p. 117) as if leaders set out to not do those things, and says teams should focus on “building trust with your counterparts” (p. 128) as if teams prioritize division and mistrust


# Thoughts
The book would have been better served by limiting it to the best practices evangalized in Part 1 and completely dropping the journey into psychometry and the nonsensical testimonial of ING Netherlands. If you subtract those parts I’d give the book a strong B+.

I share a lot of the values Forsgren espouses but many are easier said than done. E.g. we can all praise the concept of DevOps and frequent, automated deployments but I don’t have a magic wand that I can wave and suddenly make that happen for legacy systems like the Drupal CMS or PPS or others like it.

At large enterprises it’s an ultra-marathon to turn the battleships around and it often feels like books like these are overly optimistic about how easy it is to implement these things on legacy systems. The book doesn’t address how to juggle prioritization, staffing, budget, PMing, etc, just close your eyes and wish velocity and continuous integration into existence.

Written: December 2019