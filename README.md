**Abstract** \
Many theories of communication claim that perspective-taking is a fundamental component of the successful design of utterances for a specific audience (e.g. Sperber & Wilson, 1995; Clark, 1996). The present study aimed to investigate perspective-taking as a stand-alone mechanism in a constrained communication situation. Participants played a word guessing game where each trial required them to communicate a target word without context. In each game consisting of six rounds, pairs of participants took turns giving and receiving clues to guess target words, both receiving full feedback (correct/incorrect, target, and guess) after each trial. In Experiment 1, none of the measures of participants’ performance improved over rounds, suggesting either that participants were unable to improve their perspective-taking of their own accord or that the task was simply too demanding for other reasons. In Experiment 2, I tested whether this lack of improvement was due to overall difficulty rather than inability to take perspective. With more elaborate feedback (including suggestions for better clue words) and easier target items, performance did appear to improve. The results of these two experiments show that perspective-taking is effortful and demanding when there is no context to ground either signal choice or interpretation.

**Key words** \
Communication, perspective-taking, audience design, interaction, word associations

First Header | Second Header
------------ 
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

**Data dictionary**

Variable | Levels/values | Comments
------------ | ------------- | -------------
Condition | 0 = Experiment 1, 1 = Experiment 2 |
Trial_no | 1-120 |
Round_no | 1-6 | Only actually meaningful in Experiment 1 where each round was 50/50 balanced with symmetric and asymmetric target words
Success | 0 = Incorrect, 1 = Correct |
RT | Trial duration in seconds |
FAS_d | Forward Association Strength (director) | Probability of clue given target
BAS_d | Backward Association Strength (director) | Probability of target given clue
FAS_m | Forward Association Strength (matcher) | Probability of guess given clue
BAS_m | Forward Association Strength (matcher) | Probability of clue given guess
clue_rank | Rank of clue given | Of all possible clues, how did this one rank?
guess_rank | Rank of guess given | Of all possible guesses, how did this one rank?
oc_c_ratio | Ratio between optimal clue and clue given | The smaller the ratio, the better
clue_zipf | Zipf value of the clue | The smaller this value, the rarer the word
max_BAS | AS from the optimal clue to the target word | How strongly did the best clue cue the target?
symmetry | 0 = Asymmetric, 1 = Top 3 symmetric, 2 = Top 1 symmetric | Asymmetric targets are not in turn cued by their top associate. Symmetric target words are backwards cued by their top associate.
difficulty | 1 = Most difficult quantile, 2 = Secondmost difficult quantile, 3 = Thirdmost difficult quantile, 4 = Least difficult quantile | Binned according to the BAS of the best clue word
