---
name: elements-of-style
description: Strunk & White's Elements of Style, adapted for technical and player-facing prose. Use when writing or revising text people will read (server guides, READMEs, docs, GitHub issues and PRs, release notes, in-game text, player explanations) or when asked to edit, tighten, or proofread a draft.
---

# Elements of Style

The principles of Strunk & White's *The Elements of Style* (4th ed., 2000), restated in our own words and examples and adapted for documentation, issue trackers, coursework, and game text. Tags such as R14 or V8 give the matching rule in the book, for anyone who wants to look it up.

Picture the reader as lost and short on time. Every rule below exists to get that reader to the point quickly and leave no doubt about what you mean. Judge a version by how easily the reader follows it, not by its word count: a longer version that reads more clearly is the better one.

## Pick the pass

Size the effort to the piece.

- **Light pass**: short engineering text, such as README notes, GitHub issues and PRs, commit messages, release notes, and code comments. Engineers read these for the facts, in a terse register they already expect.
- **Full pass**: writing aimed at readers, such as server guides, player explanations, long docs, coursework, and in-game text.

### Light pass

1. **Proofread** against [USAGE.md](USAGE.md).
2. **Tighten.** Cut padding, softeners, and hedges on things the writer saw firsthand (R15, R17, V8). Keep the writer's shape and terse register. Add a heading or section only when the reader could not find something without it.

### Full pass

1. **Plan.** Name the reader and what they must know or do when they finish. Pick the shape before the first sentence: numbered steps for a how-to, a table for many like items, short sections under headings for a guide. Done when you can state the point in one sentence.
2. **Draft** plainly, in the words that come to you first. Polish belongs to step 3.
3. **Revise.** Reread as the reader would. Apply every composition rule to every paragraph: cut, move, recast. Large rearrangements are normal at this stage, even for skilled writers. Done when each paragraph has passed the whole list.
4. **Proofread** against [USAGE.md](USAGE.md): punctuation, form, and words people often get wrong.

**The writer owns the facts** (either pass). Take their facts, numbers, and guesses as given, and change only how they are said. This skill covers style; checking facts is a separate job.

**Editing someone else's draft** (either pass): keep their voice, their meaning, and whatever structure works. Change only what a rule justifies. Return the revised text, then a short list of the main changes, each tagged with its rule. Where the meaning is unclear, ask: rewriting a vague sentence means guessing what the writer intended.

## Composition rules

**Structure**
- **Plan the shape and keep to it** (R12, V3). A short note can grow as it goes; anything longer needs at least a rough outline, or it wanders. Even writing driven by feeling has a direction.
- **A paragraph covers one topic** (R13). Its first sentence names the topic or links it to the paragraph before. A short subject may fit in one paragraph; check afterwards whether splitting helps. Break up long slabs of text, but a string of one-sentence paragraphs reads like advertising. In dialogue, each new speaker gets a new paragraph.

**Sentences**
- **Prefer the active voice** (R14). "MES spawns the convoy" beats "The convoy is spawned by MES". Use the passive when the thing acted on is what the paragraph is about. Replace *there is*, *it is*, *could be seen* with a verb that does something. A stronger sentence usually comes out shorter.
- **State things positively and commit** (R15). Say what is: "arrives late" beats "doesn't arrive on time very often". Use *not* to deny or to contrast, never to avoid committing. Keep *may, might, could, should, would* for real uncertainty; hedging every sentence drains the writing of authority. Being plainly wrong does less harm than being vague, and a wrong claim at least gets corrected.
- **Be specific and concrete** (R16). Name the block, the number, the command, the file. "Despawns after 30 minutes" beats "despawns eventually". Back every general principle with an example. Pick the details that matter, not every detail.
- **Cut every word that does no work** (R17). This doesn't mean short sentences or thin detail; it means nothing is there for padding. Cut on sight: *the fact that, in order to, the question of whether, it should be noted that, is able to, who is, which was, in terms of, basically, actually*. If several small sentences build up one idea, merge them into one.
- **Vary the sentence pattern** (R18). A run of "X happened, and Y happened" sentences turns into a drone. Recast some as simple sentences, as two clauses joined by a semicolon, or as sentences that hold the main point until the end.
- **Give parallel ideas parallel form** (R19). Every item in a list takes the same grammatical shape: all verbs, all nouns, or all full sentences. A word that applies to every item (*the, in, to*) appears once before the first item or before every item. Paired words (*both…and, either…or, not only…but also, first…second*) take the same construction after each half. Long sets of like items go in a table, or get grouped and parallel within each group.
- **Keep related words together** (R20). Put each modifier next to the word it modifies, especially *only* and *not all*. Don't separate subject and verb with a phrase that could go at the front. Put *which* and *who* right after the noun they refer to.
- **Keep one tense** (R21). Docs and summaries stay in the present. Say once that what follows is a summary, then skip the repeated *he said*, *the author adds*. In analysis, argue a point with evidence rather than retelling the source in order.
- **Put the key words last** (R22). The end of a sentence carries the most weight, so the new fact goes there. The start is the second-strongest spot. The same holds for the last sentence of a paragraph and the last paragraph of a page.

**Style** (Chapter V)
- **Keep the writer out of the way** (V1). Draw attention to the subject, not to the author. A careful, honest writer doesn't need to chase a style; one emerges.
- **Write naturally** (V2), then check the result anyway. Read good writing; you absorb what you admire.
- **Build on nouns and verbs** (V4). Adjectives and adverbs can't rescue a weak or wrong noun.
- **Rewrite** (V5). First drafts are raw material. Keep the old version while you try changes.
- **Don't overwrite** (V6). Ornate prose tires the reader. Fast typing breeds extra words, so reread later and cut hard.
- **Don't overstate** (V7). One exaggeration makes the reader doubt everything around it. Words like *best, every, never, completely* must be literally true.
- **Drop the softeners** (V8): *very, rather, pretty, little, quite, really, somewhat*.
- **No forced chattiness** (V9). Hype, gimmicky slang, and self-display show the writer has nothing to say. Open with the news.
- **Spell normally** (V10). No *thru, nite, pls* in prose.
- **Don't over-explain** (V11). Give the reader what they need and stop. In dialogue, let the words carry the tone instead of adverbs after *said*.
- **No awkward adverbs** (V12). Skip *-ly* words people never say aloud (*overly, thusly, tiredly*).
- **Make the speaker clear** (V13). Readers must always know who is talking. Put *she said* where a speaker would naturally pause.
- **Pick the plain word** (V14). *Use* over *utilize*, *help* over *facilitate*, *start* over *commence*; short everyday words over long formal ones. Trust your ear: ending on a preposition, splitting an infinitive, or dropping *that* is fine when it reads better and stays clear.
- **Dialect only with a good ear** (V15), kept consistent, and as little of it as does the job.
- **Be clear** (V16). Nothing else in writing pays off as reliably as clarity. When a sentence tangles, start over instead of patching it; usually it wants to be two sentences.
- **Opinion only where it serves** (V17). An issue reports what happens; a guide tells the reader what to do. Offer a view when the reader asked for one or a decision depends on it.
- **Figures of speech sparingly** (V18). One image at a time, and never two clashing images in one sentence.
- **Spell names out first** (V19). Give a name or acronym in full on first use unless every reader surely knows it; abbreviate after that. Where the project keeps a glossary, use its terms.
- **Use other languages only where needed** (V20).
- **Prefer standard words to fashionable ones** (V21). Business and marketing words (*leverage, actionable, impactful, synergy, finalize, -wise*) make ordinary things sound grand and say less. Use the plain term. New coinages belong in conversation until they settle into the language.

**Attitude**: respect the reader's intelligence; condescension shows in the prose. Write to meet your own standard rather than to follow a trend.

## When to break a rule

Skilled writers do break these rules, and when they do, the sentence gains something in return. Break one only when you can say what the reader gains.
