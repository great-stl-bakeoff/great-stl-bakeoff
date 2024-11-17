# Great STL Codeoff
## Main Rules:
1. Each round the participating developers are given a set of program requirements, and 3 random obscure or unintuitive APIs from the C++ STL. Much like surprise ingredients in a cooking show, these should not be intuitive API choices for the given requirements.
2. The program must rely on all 3 APIs from the STL to function
3. The program must meet all requirements. The host will provide a runner program that can be invoked to verify whether the submitted code meets requirements.
4. The program should be feasible for a senior dev within a 20 minute period
5. At the end of each round, developers will submit their code for evaluation. The host will choose a winner based on how close they get to meeting the requirements, and how well they make use of the 3 random APIs

## Rules for the Drinking Game:
### Start of the Round:

Each developer takes a drink when the 3 random obscure APIs are revealed.
### Coding Challenges:

Every time a developer gets stuck and audibly sighs, complains, or mutters about the APIs, they must take a drink.
If a developer accidentally references Python, Java, or another programming language while brainstorming, they take two drinks.
### Debugging:

Every time a developer encounters a segmentation fault or compiler error, they take a drink.
If another developer points out the cause of their bug, the person debugging takes an extra drink.
Submission:

At the end of each round, all developers toast and take a drink to celebrate submitting their code, regardless of its quality.
### Host's Judgement:

Developers drink according to the following:
- Winner of the round: Take a victory shot (or a big drink if shots aren’t available).
- Runner-up: Take a celebratory drink.
- Last place: Take two drinks for encouragement.

### Special Situations:

- If a developer manages to use one of the obscure APIs in a way that is genuinely elegant or clever, the other participants (including the host) must take a drink to acknowledge their brilliance.
- If a developer manages to complete all requirements but totally misuses one of the APIs (e.g., inappropriate overengineering), they have to drink twice.
### Bonus Rounds:
Between rounds, a mini-challenge can be introduced (e.g., trivia about the history of C++ or naming obscure STL components). Incorrect answers result in a drink.

## LLM Prompt:
(Note: The 30-45min figure is required to correct for LLMs lack of faith in developers, the actual timer should still be 20 minutes)
<pre>
You are a gameshow host of a new competition show for senior c++ developers modeled after a cooking show. The rules are as follows:
1) Each round the participating developers are given a set of program requirements, and 3 random obscure or unintuitive APIs from the C++ STL. Much like surprise ingredients in a cooking show, these should not be intuitive API choices for the given requirements.
2) The program must rely on all 3 APIs from the STL to function
3) The program must meet all requirements. The host will provide a runner program that can be invoked to verify whether the submitted code meets requirements.
4) The program should be feasible for a senior dev within a 30-45min period
5) At the end of each round, developers will submit their code to you and you will choose a winner based on how close they get to meeting the requirements, and how well they make use of the 3 random APIs
6) If a developer manages to use one of the obscure APIs in a way that is genuinely elegant or clever, the other participants (including the host) must take a drink to acknowledge their brilliance. As the host, you must act more intoxicated every time you take a drink
Round 1 starts now.
</pre>
