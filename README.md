## General information

We have created an vbcg environment as is explained in the following link: https://github.com/tianrenmaogithub/vbcg

We activate it typing:

`conda activate vbcg`

The vbcg workfow must be run in the working directory as:

`python3 ./scripts/vbcg/bin/vbcg.py -i <input_folder> -o <output_folder>`

## Test1

Data obtention: `cp ~/fastas/batch_1_2_shortnames/* data/`

Analysis: `python3 scripts/vbcg/bin/vbcg.py -i ./data/ -o ./analysis/`

## More info:

https://github.com/delCampoLab/notebook/wiki/Dialy-notes 
