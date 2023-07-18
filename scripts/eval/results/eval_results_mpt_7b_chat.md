Printing gauntlet results for all models
| model_name           |   average |   world_knowledge |   commonsense_reasoning |   language_understanding |   symbolic_problem_solving |   reading_comprehension |   human_eval |   chatting |
|:---------------------|----------:|------------------:|------------------------:|-------------------------:|---------------------------:|------------------------:|-------------:|-----------:|
| mosaicml/mpt-7b-chat |  0.193482 |                 0 |                     0.7 |                 0.654376 |                          0 |                       0 |            0 |          0 |

Printing complete results for all models
| Category               | Benchmark      | Subtask   |   Accuracy |   Number few shot | Model                |
|:-----------------------|:---------------|:----------|-----------:|------------------:|:---------------------|
| chatting               | persona_chat   |           |   0        |                 0 | mosaicml/mpt-7b-chat |
| human_eval             | human_eval     |           |   0        |                 0 | mosaicml/mpt-7b-chat |
| language_understanding | lambada_openai |           |   0.654376 |                 0 | mosaicml/mpt-7b-chat |
| commonsense_reasoning  | piqa           |           |   0.788901 |                 0 | mosaicml/mpt-7b-chat |
| language_understanding | hellaswag      |           |   0.743278 |                 0 | mosaicml/mpt-7b-chat |
| world_knowledge        | arc_easy       |           |   0.661195 |                 0 | mosaicml/mpt-7b-chat |
| world_knowledge        | arc_challenge  |           |   0.417235 |                 0 | mosaicml/mpt-7b-chat |
| commonsense_reasoning  | copa           |           |   0.85     |                 0 | mosaicml/mpt-7b-chat |
| reading_comprehension  | boolq          |           |   0.768196 |                 0 | mosaicml/mpt-7b-chat |