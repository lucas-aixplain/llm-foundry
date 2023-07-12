Printing gauntlet results for all models
| model_name              |   average |   world_knowledge |   commonsense_reasoning |   language_understanding |   symbolic_problem_solving |   reading_comprehension |
|:------------------------|----------:|------------------:|------------------------:|-------------------------:|---------------------------:|------------------------:|
| EleutherAI/gpt-neo-125m |  0.126011 |         0.0856441 |                 0.25568 |                 0.221452 |                          0 |               0.0672783 |

Printing complete results for all models
| Category               | Benchmark      | Subtask   |   Accuracy |   Number few shot | Model                   |
|:-----------------------|:---------------|:----------|-----------:|------------------:|:------------------------|
| language_understanding | lambada_openai |           |   0.375121 |                 0 | EleutherAI/gpt-neo-125m |
| commonsense_reasoning  | copa           |           |   0.63     |                 0 | EleutherAI/gpt-neo-125m |
| commonsense_reasoning  | piqa           |           |   0.62568  |                10 | EleutherAI/gpt-neo-125m |
| language_understanding | hellaswag      |           |   0.300836 |                10 | EleutherAI/gpt-neo-125m |
| world_knowledge        | arc_easy       |           |   0.402357 |                10 | EleutherAI/gpt-neo-125m |
| world_knowledge        | arc_challenge  |           |   0.226109 |                10 | EleutherAI/gpt-neo-125m |
| reading_comprehension  | boolq          |           |   0.533639 |                10 | EleutherAI/gpt-neo-125m |