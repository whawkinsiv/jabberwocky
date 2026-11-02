---
name: jabberwocky
description: Packs words from Lewis Carroll's "Jabberwocky" (frabjous, vorpal, frumious, galumphing, slithy, burble, chortle, beamish, manxome, Callooh! Callay!) into the user's own text, in place of ordinary words with a related meaning. The original sentences, format, and facts stay intact. Use this skill whenever the user wants text "jabberwockified," "Jabberwocky style," rewritten "like Lewis Carroll" or "Looking-Glass" style, or wants Carroll's nonsense words worked into an email, post, comment, status update, notes, or file — even if they do not name the poem exactly. Not for explaining or analyzing the original poem.
argument-hint: "[text to rewrite, or a path to a file]"
---

# Jabberwocky

Keep the user's text. Swap as many of its ordinary words as you can for words from "Jabberwocky." The result must read as the same text, thick with Carroll's words.

## Find the input

$ARGUMENTS

- If the text above is a path to a file, read the file and rewrite its contents.
- If the text above is empty, rewrite the text that the user gave in the conversation.
- If there is no text anywhere, ask the user for the text in one short sentence. Then stop.

## Rules

1. **Keep the original text.** Keep every sentence, the sentence order, the format (paragraphs, bullets, greeting, sign-off), and the approximate length. Do not turn the text into a poem. Do not add rhyme, rhythm, stanzas, a title, or new sentences. The user wants their own text, not a new text that copies the shape of the poem.
2. **Swap heavily.** Swap every word that has a poem word with a related meaning, mood, or sound. Aim for two or three swaps in each sentence. Easy targets are praise words (great, nice, smart), size and strength words (huge, real, super, really), and verbs of talking, searching, and moving. The sentence structure and the small words (the, of, and, is) stay, so the reader can still follow the text. If the user asks for a lighter touch, swap about one word per sentence.
3. **Use only words from the poem.** Take each word from the word list below. You can add normal English endings and prefixes (-s, -ed, -ing, -ly, -ness, un-), as in "burbled," "frumiously," or "unmimsy." Do not invent new blends, because a new blend is not a word from the poem.
4. **Match loosely, not randomly.** The poem word must share something with the original word: its meaning, its mood, or its sound. "Clever" becomes "vorpal" (meaning). "Super" becomes "frumiously" (mood: intense). "Website" becomes "wabe" (sound). The context must still let the reader guess the original word.
5. **Keep the grammar correct.** You can change a small word or two so that the swap fits ("before sending" becomes "before you galumph it out"). Every sentence must still parse as normal English.
6. **Keep the facts.** Do not change names, product names, numbers, dates, prices, links, or technical terms.
7. **Vary the words.** Prefer a different poem word for each swap. Reuse a poem word only after you use the other words that fit, or when it refers to the same thing again.
8. **Punctuate exclamations cleanly.** Inside a sentence, write "Callooh! Callay!" with commas: "Callooh, callay on the launch!" Keep the exclamation marks only when the exclamation stands alone.

## Word list

| Poem word | Carroll's meaning | Use it in place of |
|---|---|---|
| brillig | four in the afternoon, the time to start broiling dinner | afternoon, late in the day, time |
| slithy | lithe and slimy | slick, slippery, slimy, sleazy, spammy, sneaky, smooth |
| tove | a creature like a badger, a lizard, and a corkscrew | people, users, folks, customers, creatures, small odd things |
| gyre | to go round and round, like a gyroscope | spin, circle, loop, scroll, browse, cycle |
| gimble | to make holes, like a gimlet | dig, drill, poke, search, hunt, find |
| wabe | the grass plot around a sundial | place, space, area, yard, site, forum, board, web |
| mimsy | flimsy and miserable | weak, flimsy, sad, shoddy, bad, poor, boring |
| borogove | a thin, shabby bird, like a live mop | a scruffy person or thing, a newcomer |
| mome | lost, far from home | lost, stray, confused, random |
| rath | a sort of green pig | creature, critter, user |
| outgribe, outgrabe | to bellow and whistle, with a sneeze in the middle (outgrabe is the past tense) | shout, complain, cry out, rant |
| Jabberwock | the monster | the big problem, the main threat, a pain, a headache, the hard part |
| Jubjub bird | a danger to avoid | a second threat, a risk, a distraction |
| Bandersnatch | a fierce, fast creature | a bug, a pest, a rival, a spammer, a bot |
| foe | enemy | problem, competitor, obstacle |
| slay, slain | kill, killed | beat, crush, solve, fix, finish |
| shun | avoid | avoid, skip, ignore |
| frumious | fuming and furious | angry, furious, fierce, intense, wild, super, very |
| vorpal | keen and deadly | sharp, smart, clever, powerful, effective, killer |
| vorpal blade | the hero's weapon | the tool, the fix, the feature |
| manxome | fearsome | hard, daunting, huge, tough, big, scary |
| Tumtum tree | the place where the hero rests | a rest stop, a break, a pause |
| uffish | gruff, rough, and huffish | gruff, grumpy, deep, thoughtful, careful |
| whiffle | to blow in short puffs | drift, wander, come along, show up, arrive, go out |
| tulgey | thick and dark | dense, messy, tangled, confusing, crowded, noisy |
| burble | to bleat, murmur, and warble | talk, chatter, ramble, ask, post, comment, reply, write, say |
| snicker-snack | the sound of a quick blade | quick, quickly, fast, cleanly, in one stroke |
| galumph | to gallop in triumph | go, return, march, launch, ship, send, move proudly |
| beamish | radiant, beaming | proud, happy, bright, cheerful, glad |
| frabjous | fabulous and joyous | great, wonderful, nice, excellent, awesome, amazing, best |
| chortle | to chuckle and snort | laugh, cheer, smile, celebrate |
| Callooh! Callay! | a cry of joy | hooray, yay, congrats, woohoo |
| beware | (a real word that the poem made famous) | watch out, be careful |
| 'twas | it was | it was |
| thy, hast thou | your, have you | your, have you |

Phrases from the poem can replace an ordinary phrase of the same meaning:

| Poem phrase | Use it in place of |
|---|---|
| in uffish thought | thinking hard, after some thought |
| O frabjous day! | what a great day, great news |
| one, two! one, two! | step by step, quickly, in order |
| my beamish friend | my friend, buddy, you (in praise) |
| with eyes of flame | fiercely, eagerly, intensely |
| long time the foe they sought | searched for a long time |

## Output

Give only the rewritten text. Do not write an introduction such as "Here is your text," and do not add comments after the text.

If the user asks what the words mean, or asks for a glossary, add a short list titled "Humpty Dumpty's notes" after the text. Give each poem word and the original word it replaced, for example: "*slithy* — spammy."

If the input came from a file and the user asks to save the result, write it next to the original file as `<name>.jabberwocky.md`. Otherwise, print the result in the conversation.

## Example

Input:

> Great post! Writing cold emails is a huge headache for most founders, and your tip about mentioning a specific detail from the prospect's website is really clever. I love that you test every subject line before sending. Thanks for sharing, this is super helpful!

Output:

> Frabjous post! Burbling cold emails is a manxome Jabberwock for most founders, and your tip about mentioning a specific detail from the prospect's wabe is really vorpal. I love that you test every subject line before you galumph it out. Thanks for sharing, this is frumiously helpful!

The output keeps every sentence and every fact. It makes eight swaps: "great" becomes "frabjous," "writing" becomes "burbling," "huge headache" becomes "manxome Jabberwock," "website" becomes "wabe," "clever" becomes "vorpal," "sending" becomes "you galumph it out," and "super" becomes "frumiously." It keeps "founders" and "subject line," because those words carry facts.
