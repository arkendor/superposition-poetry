# Superposition Poetry
A 100% client-side interface for creating and reading superposition poems. 

Each superposition has a list of words it can collapse into, specified by the author, and a probability matrix determining which word appears based on other events in the poem. 

This gives artists another way to introduce ambiguity into language, encode multiple meanings within a single poem, and tell stories through intentionally chosen probabilities.

To try it, download [superposition_poem_editor.html](superposition_poem_editor.html) and open it in your browser. You can also import [The_Stranger_arkendor_superposition_poem.json](The_Stranger_arkendor_superposition_poem.json) to explore an example.

## What can you do with Superposition Poetry?

Some new features of this superposition-poem system include:

1. You're able to encode multiple meanings into one poem without having to make every possible combination of words make sense. Without conditional matrices, just 10 superpositions with 2 choices each would give you 1,024 possible readings, and you'd have to account for every single one! This seriously limits what you can write, since every alternative has to work with every other alternative. With conditional matrices, you can instead link words together, giving you the freedom to write wildly different stories within the same poem without accidentally mixing them into nonsense. Matrices let the author specify which readings they want to allow, and which ones to rule out entirely.

2. You now have a whole new dimension to play with in terms of narrative significance: just like spatial poems where the layout of the words conveys information, in superposition poems the specific probabilities also convey information: there's a large difference between a 50/50 and a 99/1. A happy ending that happens 99% of the time conveys something very different from one that happens only 1% of the time.

3. You can interpolate multiple poems in one piece: even just starting with a 50/50 choice and setting the remaining conditional weights to 0 or 1 allows you to get a poem that's a complete coinflip between one passage and another. Using intermediate probabilities allows you to specify where you want the different poems to intersect and combine with each other.

4. You also don't even have to use it for poetry: any form of words works really. You could use it for a witness statement that leaves the true culprit unresolved, or to represent different possible event chains in a short story.

But honestly, do whatever you want with the format. No one should define art.

## License

The Superposition Poetry editor is licensed under the [MIT License](LICENSE).

[*The Stranger*](The_Stranger_arkendor_superposition_poem.json) © 2026 arkendor. All rights reserved. Linking, citation, and discussion are welcome; republication or adaptation requires permission except as permitted by law.

The MIT License applies only to the editor, not to the poem.
