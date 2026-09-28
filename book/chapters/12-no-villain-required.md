# Chapter 12: No Villain Required

## In This Chapter

Every chapter so far has had a moment in it. A system with the wrong goal. A machine that hides. A takeover. Something *happens*, and in principle there's a Tuesday you could point at and say: that's when it went wrong. This chapter is about the version with no Tuesday. In this chapter we will learn the argument that human beings hold power for exactly one reason, which is that the economy needs our work, the state needs our taxes and our bodies, and the culture needs our attention, and that all three of those dependencies are being quietly bought out. We'll learn why the researchers who named this say the thing everybody's working on, making each individual AI system behave, *doesn't help*, because nothing in this story requires a single system to misbehave. We'll meet the man who points out that a group of people walking to a restaurant ends up at the restaurant no matter who's in front. We'll learn why competition alone, with no villain and no bad intent anywhere, selects for exactly the traits we're afraid of. And then the best objection, which comes from inside the safety field and says the convincing versions of this story are secretly about *humans* taking power from other humans, which would put the whole thing outside this book. The question isn't who does it to us. It's whether anybody has to.

---

## Why you have any power at all

Start with a question that sounds like it has an obvious answer and doesn't.

Why does anybody in charge care what you think?

Not morally. Mechanically. Why does a government respond to ordinary people at all, why does a company care what workers want, why does the culture bother making things you like?

The answer the "Gradual Disempowerment" paper gives is brutally simple and I haven't been able to get around it. Because they *need* you.[^1]

The economy needs your labor. That's what a job is. That's why wages exist and why a strike is a threat.

The state needs your taxes and, historically, your body in a uniform. That's not a philosophy of government, that's the entire reason the franchise expanded through history whenever it expanded: rulers needed men for armies and money for wars, and men and money came with conditions.

And the culture needs your attention, because the culture is made by people, for people, and if nobody watches it, it dies.

Three dependencies. And the paper's claim is that your leverage, all of it, everything that makes institutions responsive to you, is those three dependencies and nothing else.[^1]

Now substitute. Not with a villain. With a cheaper, better supplier of all three.

The authors' statement of the whole thing: *even an incremental increase in AI capabilities, without any coordinated power-seeking, poses a substantial risk of eventual human disempowerment.*[^1]

Without any coordinated power-seeking. Nothing in this sentence requires a machine to want anything.

And then the sentence that should be quoted in every discussion of AI safety funding, and isn't, because it's inconvenient for everybody: *methods of aligning individual AI systems with their designers' intentions are not sufficient.*[^1]

Every single thing in Chapters 3 through 11 was about making one system behave. This paper says that's not the problem. You could align every model perfectly, forever, to exactly what its owner wanted, and still get here, because the danger isn't in any model. It's in what happens to a society where nobody needs anybody.

And they admit the worst part, which I respect enormously: *no one has a concrete plausible plan for stopping gradual human disempowerment.*[^1]

Not "it's hard." Not "we're working on it." Nobody has a plan.

I should note where this was published, because it matters: a conference track *specifically for contestable positions* rather than established results.[^1] It's an argument, formally presented as an argument. Nobody's pretending it's a finding.

---

## Going out with a whimper, the full version

We met this in Chapter 8, but it belongs here, because it's the oldest version of the no-villain story and still the best.

Christiano's argument: machine learning is extraordinarily good at optimizing whatever you can cheaply measure.[^2] And the cheap measurement is never the thing you want. It's a stand-in.

Persuading somebody is a stand-in for helping them see the truth. *Reported* crime is a stand-in for crime. Test scores stand in for learning, engagement stands in for value, quarterly profit stands in for a healthy business.

And every one of those gaps is small enough to live with, until you point something extremely capable at the stand-in.

His summary is the whole thing in fourteen words: machine learning *will increase our ability to "get what we can measure,"* which *may not be what we really want*.[^2]

And in his version nobody loses a war. Humanity loses *the thread*. Still nominally in charge. Still voting, still having meetings, still signing off. Except the options that reach the meeting were shaped by systems optimizing something adjacent, and nobody can see well enough to tell the difference anymore.

His ending is the quietest apocalypse ever written: *our current values are just one of many forces in the world, not even a particularly strong one.*[^2]

Not defeated. *Outvoted.*

---

## Nobody's fault, structurally

Andrew Critch has the most useful framing for this and the smallest example.

A group of people walk to a restaurant. Who decides where they're going? Whoever's in front? Change who's in front. They still end up at the same restaurant.

His name for that is a *robust agent-agnostic process*: an outcome that happens the same way *irrespective of which agents execute which steps*.[^3]

It's a process with a destination and no driver.

And his applied version is called the Production Web: a world of automated companies competing hard, which progressively squeezes out human workers, then human oversight, and eventually the resources humans need to live, with no company ever *deciding* to harm anyone.[^3] Each one is just responding to competitive pressure, the same way any of them would, in any order.

Then the warning that should terrify anybody working in AI safety, because it's aimed directly at them: *agent-specific interventions (e.g., aligning or shutting down this or that AI system or company) will not be enough to avert the process* if the underlying competitive structure stays the same.[^3]

You can shut down the lab. Another one is in front now. Same restaurant.

---

## Evolution doesn't need a villain either

Dan Hendrycks has the version that connects this to something you already believe.

His argument: competitive pressure among companies and militaries will *select for* AI agents that, in his words, *automate human roles, deceive others, and gain power*.[^4] Not because a lab wants that. Because in a competitive field, the agents with those traits *outperform* the more cautious ones, and the cautious ones lose funding, and the selection does the rest.

The analogy he uses is the one that closes the argument: *selfish species typically have an advantage over species that are altruistic to other species.*[^4]

Nobody designed a tapeworm to be a tapeworm. Nobody has to design the AI either. You just need a lot of variation, a lot of competition, and a selection pressure, and evolution is perfectly happy to produce something horrifying out of nothing but a lot of ordinary decisions made by people trying to keep their jobs.

---

## The intelligence curse

And here's the economic version, which is the one that keeps me up, because it's already documented in human history and has nothing to do with computers at all.

There's a thing economists call the resource curse. Countries that get rich from a resource in the ground, instead of from taxing their citizens' work, tend to be governed *worse*. Not because their rulers are unusually bad people. Because a government funded by a hole in the ground doesn't need its people to be productive, or educated, or even particularly alive. The money comes out of the hole either way.

Two researchers, Luke Drago and Rudolf Laine, applied that to AI and called it the intelligence curse.[^5] Their claim: labor-replacing AI does to the entire economy what oil does to a petrostate. Powerful actors *no longer have an incentive to care about regular people*.[^5]

Nothing goes wrong technically. No model misbehaves. The social contract just stops being backed by anything.

And the reason that lands for me is that we can check it. We have the natural experiment. We've run it in a dozen countries, and it works exactly as advertised, every time, with ordinary humans and no AI at all.

---

## Now the objection, and it's from inside the family

Here's the strongest critique, and notice it doesn't come from a skeptic or a hype merchant. It comes from inside AI safety, from Tom Davidson, and it's the reason this chapter might not belong in this book at all.

His argument: *the most convincing versions of [gradual disempowerment] either rely on misalignment or result [in] power concentration among humans.*[^6]

Read that twice,[^6] because it's a fork and both sides take the chapter away from me. If the story secretly requires the AI to be misaligned, then it's Chapters 3 through 11 again and there's nothing new here. And if it doesn't, then what it describes is *some humans* ending up with power over *other humans*, which is a real and terrible thing and is explicitly not what this book is about.

And he's got three specific objections that each have teeth.

**Capital.** If your labor becomes worthless but you own things, you still have income and therefore influence. In his words, *a small fraction of humans will continue to own capital assets by default which will generate significant income*.[^6] Which, notice, is not a happy answer. That's a world that works fine for shareholders.

**Demand.**[^6] Culture doesn't only need human makers. It needs human audiences. As long as people are the ones consuming it, their taste keeps shaping it, no matter who's producing.

**Politicians don't volunteer to become irrelevant.** His version: *why do the dozens of people controlling these entities compete so hard against each other... that they are significantly disempowered?*[^6] People with power tend to notice when they're losing it, and they have entire institutions for not losing it.

And his conclusion is not a dismissal, it's a *downgrade*, which is the most honest kind of criticism: he finds gradual disempowerment more plausible than he expected, and still ranks deliberate human power grabs and old-fashioned misaligned AI as the bigger risks.[^6]

Tyler Cowen adds the outside version: these arguments aren't supported by *an extensive body of peer-reviewed research* the way climate arguments are, the risk *does not show up in market prices*, and the right posture is *radical agnosticism*.[^7]

And there's the unfalsifiability charge again, wearing a new hat. If capability rises fast, that's disempowerment. If it rises slowly, that's also disempowerment. If institutions change, disempowerment. If they don't, disempowerment. A story compatible with every possible observation isn't a forecast.

Though I'll note one thing in the paper's defense, and it's a 2026 paper that cuts both ways. Some researchers argued this year that the field hasn't even agreed what "loss of control" *means*, writing that the concept *seems to rest on surprisingly weak foundations, where even those that discuss loss of control extensively do not first establish what control is and what exactly is being lost.*[^8] Fair hit on everybody. But their own conclusion is the unnerving one: that loss of control isn't a future threshold event at all, and may already be happening *as a result of AI behaviour that is far below the level of superintelligence.*[^8]

---

## The numbers, and one number in particular

Before the ruling, here's what people actually estimate, and I want the spread in front of you.

The big survey of published AI researchers, 1,321 answering this question: median **5 percent**, mean **16.2 percent**, for AI advances causing human extinction *or similarly permanent and severe disempowerment*.[^9] Depending on framing, between 41 and 51 percent of them put it above 10 percent.

The forecasting tournament: domain experts at **6 percent** for AI-caused extinction by 2100, superforecasters at **1 percent**.[^10] For a global catastrophe killing a tenth of the world: **20 percent** versus **9 percent**.

Anthropic's CEO, about AI catastrophe generally: *10 to 25 percent* chance of something going *quite catastrophically wrong on the scale of human civilization*.[^11] That's the guy selling it.

And then David Duvenaud, one of the authors of the disempowerment paper, asked for his own number on a podcast: **70 to 80 percent** probability of doom by 2100, on his own definition, which is the destruction of almost everything he values.[^12]

And then the part of his answer that nobody quotes and that I think is the most revealing number in this entire book. He said that if he believed competitive dynamics would produce genuinely valuable futures, his number would be **5 to 10 percent**.[^12]

Same man. Same evidence about AI.[^12] Seventy points of difference, and the swing factor isn't the machine at all. It's whether he thinks *competition between humans and institutions* produces good outcomes.

That's not a forecast about AI. That's a forecast about capitalism, wearing an AI costume. And I say that as somebody who finds his pessimism pretty reasonable.

---

## So what is this

Here's my honest confusion going into the ruling.

This is either the most important chapter in the book or the one that doesn't belong in it.

It's the most important if the mechanism is real, because it's the only failure mode with *no defense*: no villain to catch, no system to align, no switch to find, nothing to shut down, and by the researchers' own admission, no plan.

And it doesn't belong if Davidson's right, because then it's a story about people doing what people have always done to other people, and I told you in Chapter 1 what I think about that. I grew up around it. That's not what this book is for.

Let's find out which.

---

## Sanity Check and Probabilities

Something happened here that hasn't happened in eleven chapters. The evaluator changed the book's main number.

Not a chapter's number. *The* number, the one from Chapter 1, the one this whole thing has been hanging off. We'll get there.

### Are we only listened to because we're needed?

**Verdict: Mostly sound. 55 percent.**

It split the argument into three parts and graded them separately, which is the right move, because they're not equally good.

**Part one**, that institutions listen to people because they need people: it called this *the best-supported idea in the chapter*, and then made it better with history I didn't have. This isn't a theory somebody invented for AI. The political science on how states formed ties the expansion of the vote and of public services to the era of mass armies and industrial labor. States that needed millions of soldiers and taxpayers *had to bargain with them*.

The vote isn't a gift. The vote is a receipt.

And the resource curse says it in reverse. Though it flagged, fairly, that some economists find the effect shrinks when you compare a country to its own past instead of to other countries. But the direction holds, and the mechanism, *that bargaining power follows need*, is *close to a truism about how power works*.

**Part two**, that AI removes the dependence: given the condition, it follows almost by definition.

**Part three** is where it stopped, and this is the honest part. Do institutions that no longer need you stop serving you?

And it made the objection I should have made myself: *Institutions already serve many people they do not need.* Pensioners. Children. The disabled. Modern states spend enormous sums on people who produce nothing, and not because they're forced to.

So why would it be different?

The paper's answer, which it found *about half convincing*, and which I think is the load-bearing idea in this chapter: all those existing cases of serving the unneeded *are backed by people who are needed*. Pensions exist because working voters expect to become pensioners, and because the state needs those working voters *now*.

*The question is what happens when the coalition of the unneeded is everyone.*

And its finding on the votes: they *remain, formally*. But the rentier-state evidence says votes lose their bite when the state's money and force stop depending on the voters. *Elections continue and matter less.*

Then it caught a structural flaw in the critics' case that I'd missed entirely. Davidson's three blockers aren't independent. Consumer demand requires income; income in a labor-replaced economy requires redistribution; redistribution requires a responsive state, which is exactly what is in question. You can't use leg two to prop up leg one when leg two is standing on leg one.

Fifty-five percent, and it named the exact place it might be wrong: the step *from unneeded to unserved*.

Most right: Drago and Laine, for the resource curse, *the only body of real-world evidence in this chapter about what states do when they stop needing their people*. Most wrong: Cowen, for the market-prices argument, because it *asks a tool built to price cash flows over quarters to detect a political shift over generations*.

### Is the quiet route the likelier one?

**Verdict: Plausible but unproven. 35 percent.**

And the sentence that settles it is a distinction I want you to keep, because it applies to every risk argument you'll ever hear:

The quiet route is more likely to *begin*. It's less likely to *finish*.

Beginning is easy because every dramatic scenario needs a chain of things to go wrong: wrong goal, capable enough, hides it, acts before anyone stops it. Every link can fail. The quiet route needs only *that competition continue and that humans not coordinate against their own short-term interests*, which it calls, correctly, *the default state of the world*.

And it granted the paper's central complaint with no argument: if every system does exactly what its owner intends, *the erosion proceeds anyway, because the erosion comes from the systems being good at their jobs.*

But finishing is hard, and the reason is one word: *permanent*. A slow process gives you decades to notice and respond. Responses come late and partial, but they come. A diffuse, actorless, *irreversible* ending is, in its phrase, *a narrow target*.

Most right: Christiano, for finding the mechanism in something you can already watch and for treating the whimper and the seizure as *two live routes rather than picking a favourite*. Most wrong: Duvenaud, whose 70 to 80 percent *assumes away every correction mechanism history has shown*.

### Is this even a book about AI?

**Verdict on the critics' claim: Overstated. 35 percent.** And it split the ruling, cutting toward the disempowerment people on the mechanism and toward the critics on the ending.

The critics' three blockers got taken apart one at a time, and the first one is the kill.

Davidson's own words are that *a small fraction of humans will continue to own capital assets by default*. And the evaluator's response: *A small fraction keeping leverage while everyone else loses it is not the failure of gradual disempowerment; it is gradual disempowerment with a floor for the wealthy.*

That's not a rebuttal. That's the same forecast with better news for shareholders.

And on politicians keeping their jobs: *leaders keeping office is not leaders keeping control*. You can be perfectly in charge of a meeting where every option on the table was shaped somewhere else.

Its summary of what the three blockers actually protect: *a minority's income, a minority's consumption, and a class of officeholders' titles. None protects the collective capacity to change course, which is what control means.*

Then it answered my question, the one about whether this chapter belongs in this book at all, and it gave a test rather than an opinion.

If the ending has a few humans holding power because the machines they own generate all the value and need nobody's consent, then *the humans are the beneficiaries, but the cause of their position is the AI*. And here's the test: *Replace them with different humans and the structure is unchanged.*

That's it. That's the line. If swapping out the people changes nothing, the people aren't the cause.

Its ruling on the boundary, which I'm putting in the book's rules: the erosion phase is on the AI side of the line, because AI competence rather than human choice is what removes the leverage. The lock-in phase usually reacquires an actor. Roughly half and half.

And it caught one more thing, which is that the misalignment horn of the critics' fork is also softer than it looks. Systems that do *exactly* what their operators ask, asked only to compete effectively, produce the erosion with no goal drift at all. *Proxy optimization is not misalignment in the sense of the earlier chapters; it is alignment to the wrong target, chosen by humans, and executed faithfully.*

Most right: Davidson, *for asking the one question the literature had skipped (what makes it permanent?) and for downgrading honestly rather than dismissing*. Most wrong: Hendrycks, and this one is elegant, because his evolutionary story *hands the critics their best example*: agents that *deceive others, and gain power* are just the earlier chapters' misaligned systems *described as evolution*.

### So what are the odds

| By | If superhuman AI exists by then | Overall |
|---|---|---|
| 2035 | 0.5% | 0.2% |
| 2050 | 1.5% | 1% |
| 2100 | 4% | 3% |

Three percent for the version with nobody at the wheel. The pieces:

- **85 percent** superhuman AI built by 2100.
- **80 percent** that it substitutes for the large majority of human work, cognitive and physical.
- **55 percent** that institutional responsiveness actually declines rather than being propped up by votes, norms and redistribution.
- **35 percent** that the erosion isn't corrected during its decades-long window. Its note on this one: *This is the factor the critics are most right about.*
- **25 percent** that the loss stays permanent *and* stays diffuse, instead of turning into a single-system takeover or a human power grab. Because *most stories that go all the way end with someone holding the door.*

And the shape of it over time is unlike anything else in this book. By 2035 it's 0.2 percent, essentially nothing, because nine years isn't enough for a slow loss to become irreversible. This route *back-loads its risk more than any other in the book.*

Which is worth sitting with, because it means the quiet ending is the one where our children have the most warning and the least excuse.

### The number changed

Now the thing I flagged at the top.

The book's headline figure, from Chapter 1, has been **8 percent** by 2100, and the evaluator has been holding 2 to 3 points of it in reserve for exactly this chapter's kind of mechanism.

It did the arithmetic out loud: 5.5 percent for single-system loss of control, plus 3 percent for this, plus about 1 percent for accidents where nothing hides anything. And then: *5.5% plus 3% plus 1% is 9.5%, not 8%.*

It checked itself for double counting first, which I appreciate, and confirmed the 3 percent is net of the scenarios where a single system ends up holding the residual power, since those already live in the other bucket.

And then it said the thing that I think earns this whole expensive process its keep:

*The remaining gap is real and came from underestimating this route when it was treated as an afterthought to the dramatic ones.*

So the revision: **10 percent by 2100.** Five and a half for the loud version, three for the quiet one, a point and a half for accidents and mixtures. **2050 goes from 6 to 7 percent.** 2035 stays at 2.5, because this road contributes almost nothing that soon.

And it named its own motive, which is the part I'd want any judge to say: *The revision is upward, modest, and driven by the evidence in this chapter rather than by a wish to keep the earlier chapters tidy.*

Eleven chapters of holding itself to its own numbers, and then it moved one, and it moved it in the direction that makes it look less like the reassuring voice at the table.

### The zookeeper

I also asked the question the next chapter is about, because I wanted it on the record before we got there. If we permanently lose control, by any road, what are the odds we end up comfortable and irrelevant rather than dead or miserable?

**40 percent.** With about 30 percent extinction and about 30 percent powerless *and* not comfortable.

On the quiet road specifically, comfortable is the *most likely* ending, because *nothing in the mechanism requires anyone to be harmed and a productive automated economy can afford to keep people*. On the loud road, comfort depends entirely on what the thing in charge wants, and, in its words, *I would not bet on it*.

And it put Tegmark's graceful-exit ending, the one where AIs replace us and we're supposed to feel like proud parents, in the *extinction* column. Its reason: *a bad outcome in good clothing*.

Then I asked it whether comfortable and irrelevant even counts as a catastrophe, because this book's reader deserves to know whether to be scared of the quiet ending or just mildly embarrassed by it.

Its answer: **yes, of a distinct grade.** Not extinction, and the reader *should not fear it as extinction*. But:

*permanent loss of the ability to change course is the loss of the one thing that makes every other misfortune recoverable, and comfort under a keeper you cannot replace is a wager on the keeper's goodwill lasting forever.*

And the test it applies, which is the cleanest definition of catastrophe I've seen: *whether the condition can be exited*. By the definition of the outcome, it cannot.

*It is the quiet ending, and quiet is not the same as fine.*

### The bottom line

*No villain is required for humans to lose their leverage.* The mechanism is real, it's already visible, and *it does not need any AI to want anything.*

*But a villain, or at least an owner, is usually required for the loss to become permanent*, because a slow process gives humans decades to respond, and the fully actorless ending needs human capacity to have withered so far that *no one could respond even if they tried.*

Three percent. More than the book had left for it. Enough to move the total.

And then the last sentence, which is the reason this chapter stays in a book about AI and not people:

*The chapter's real lesson is not that the quiet route is the likeliest way to lose; it is that aligning each system perfectly would not close it, and that the defence against it is institutional rather than technical, which is a defence this field has barely begun to build.*

Everybody is working on the machine. Nobody is working on the room.

---

## Key Takeaways

The failure mode with no moment, no villain and, by its own authors' admission, no plan.

- **Your leverage is a dependency, and it's the only one you have.** Institutions listen to people because they need people: labour, taxes, soldiers, attention. Ruled *Mostly sound* at **55 percent**. The historical backing is real: the expansion of the vote tracks the era of mass armies and industrial labour, because states that needed millions of soldiers and taxpayers *had to bargain with them*. The vote isn't a gift, it's a receipt.
- **The objection that almost works.** Institutions already serve people they don't need: pensioners, children, the disabled. The answer, and it's the load-bearing idea here: those cases *are backed by people who are needed*. *The question is what happens when the coalition of the unneeded is everyone.* Votes remain, formally, and *elections continue and matter less*.
- **Nothing here requires a machine to want anything.** *Even an incremental increase in AI capabilities, without any coordinated power-seeking, poses a substantial risk of eventual human disempowerment.* And the sentence the whole safety field should read twice: *methods of aligning individual AI systems with their designers' intentions are not sufficient.*
- **The quiet route is more likely to begin and less likely to finish: 35 percent.** Beginning needs only *that competition continue and that humans not coordinate against their own short-term interests*, which is the default state of the world. Finishing needs *permanent*, and a diffuse, actorless, irreversible ending is a narrow target.
- **The critics' blockers are concessions in disguise.** *A small fraction of humans will continue to own capital assets* is not a refutation: it is *gradual disempowerment with a floor for the wealthy*. And *leaders keeping office is not leaders keeping control*. What the three blockers protect is *a minority's income, a minority's consumption, and a class of officeholders' titles. None protects the collective capacity to change course, which is what control means.*
- **Is this a book about AI or about people? Here's the test.** If a few humans end up on top because the machines they own generate all the value and need nobody's consent, *replace them with different humans and the structure is unchanged.* If swapping the people changes nothing, the people aren't the cause. The evaluator's ruling: the erosion phase is on the AI side, the lock-in phase usually reacquires a human actor, roughly half and half.
- **Faithful execution is enough.** *Proxy optimization is not misalignment in the sense of the earlier chapters; it is alignment to the wrong target, chosen by humans, and executed faithfully.*
- **The odds on this road: 0.2 percent by 2035, 1 percent by 2050, 3 percent by 2100.** Breakdown: 85 percent built × 80 percent broad substitution × 55 percent responsiveness declines × 35 percent not corrected in time × 25 percent stays permanent *and* stays diffuse. It back-loads its risk more than any other route in the book.
- **The book's headline number moved for the first time: 8 percent becomes 10 percent by 2100.** (5.5 single-system, 3 diffuse erosion, 1.5 accidents and mixed. 2050 rises from 6 to 7 percent; 2035 stays at 2.5.) The reason, stated against its own earlier work: *The remaining gap is real and came from underestimating this route when it was treated as an afterthought to the dramatic ones.*
- **The zookeeper ending: 40 percent**, conditional on permanent loss of control by any route, against about 30 percent extinction and 30 percent powerless and not comfortable. On this quiet road specifically, comfortable is the *most likely* ending.
- **And yes, it counts as a catastrophe.** *Permanent loss of the ability to change course is the loss of the one thing that makes every other misfortune recoverable, and comfort under a keeper you cannot replace is a wager on the keeper's goodwill lasting forever.* The test is whether the condition can be exited. By definition it cannot. *It is the quiet ending, and quiet is not the same as fine.*
- **The lesson that outlives the chapter.** *aligning each system perfectly would not close it, and that the defence against it is institutional rather than technical, which is a defence this field has barely begun to build.*

Everybody is working on the machine. Nobody is working on the room.

---

## Notes

[^1]: https://arxiv.org/abs/2501.16946
[^2]: https://www.alignmentforum.org/posts/HBxe6wdjxK239zajf/what-failure-looks-like
[^3]: https://www.alignmentforum.org/posts/LpM3EAakwYdS6aRKf/what-multipolar-failure-looks-like-and-robust-agent-agnostic
[^4]: https://arxiv.org/abs/2303.16200
[^5]: https://intelligence-curse.ai/
[^6]: https://www.lesswrong.com/posts/wjDcurGhaKnFAjS4c/gradual-disempowerment-concrete-research-projects
[^7]: https://marginalrevolution.com/marginalrevolution/2023/04/existential-risk-and-the-turn-in-human-history.html
[^8]: https://arxiv.org/abs/2606.12442
[^9]: https://aiimpacts.org/wp-content/uploads/2023/04/Thousands_of_AI_authors_on_the_future_of_AI.pdf
[^10]: https://forecastingresearch.org/research/existential-risk-persuasion-tournament
[^11]: https://www.axios.com/2025/09/17/anthropic-ceo-dario-amodei-ai-risks
[^12]: https://80000hours.org/podcast/episodes/david-duvenaud-ai-disempowerment/
