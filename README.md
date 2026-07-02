Loop — a Claude skill for iterating, not one-shotting.
One-shot AI outputs are a trap. You ask, it answers, and you're stuck patching the same response in circles with zero structure.
So I built Loop: a Claude skill that puts any output through repeated rounds instead of treating the first response as final.
How to call it
Type /loop followed by the mode and what you want worked on:
/loop refine [paste your draft]
/loop eval [your output] against [your criteria]
/loop build [what you want constructed]
/loop compare [your options or the brief]
/loop critique [your output]
/loop feedback [your output] — then give notes each round
Or skip the syntax entirely. Just describe what you want iterated on in plain language, and Loop figures out the right mode on its own.
The six modes
→ Refine — tightens one draft across passes
→ Eval — scores the output, regenerates against the score
→ Build — constructs it step by step, not all at once
→ Compare — generates options, picks a winner
→ Critique — sharp feedback, no rewrite
→ Feedback — you drive each round with your own notes
One skill. Six ways to define "done."
