Printing gauntlet results for all models
| model_name      |   average |   world_knowledge |   commonsense_reasoning |   language_understanding |   symbolic_problem_solving |   reading_comprehension |
|:----------------|----------:|------------------:|------------------------:|-------------------------:|---------------------------:|------------------------:|
| mosaicml/mpt-7b |  0.449423 |          0.436817 |                0.604679 |                 0.695526 |                          0 |                0.510092 |

Printing complete results for all models
| Category               | Benchmark      | Subtask   |   Accuracy |   Number few shot | Model           |
|:-----------------------|:---------------|:----------|-----------:|------------------:|:----------------|
| language_understanding | lambada_openai |           |   0.703474 |                 0 | mosaicml/mpt-7b |
| commonsense_reasoning  | copa           |           |   0.8      |                 0 | mosaicml/mpt-7b |
| commonsense_reasoning  | piqa           |           |   0.804679 |                10 | mosaicml/mpt-7b |
| language_understanding | hellaswag      |           |   0.765684 |                10 | mosaicml/mpt-7b |
| world_knowledge        | arc_easy       |           |   0.723485 |                10 | mosaicml/mpt-7b |
| world_knowledge        | arc_challenge  |           |   0.431741 |                10 | mosaicml/mpt-7b |
| reading_comprehension  | boolq          |           |   0.755046 |                10 | mosaicml/mpt-7b |