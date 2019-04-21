# team004-MachineLearningModel

In order to get all the files, you will have to execute some of the shell script, which are in the folder (*You might need to sudo in order to execute some of the code below*)

  - [ ] save_transformer
  - [ ] save_word2vec
  - [ ] dataset

To startup the server/docker container execute

```
sh startup_docker.sh
```

And the everything is ready !!!


## Running Transformer

```
python3 training_transformer.py --vocabulary-size 7500 \
  --max-sen-length 20 \
  --num-layer 4 \
  --model-dim 128 \
  --pointwise-dim 512 \
  --num-head 8 \
  --dropout-rate 0.1 \
  --batch-size 64 \
  --warmup-length 400 \
```
