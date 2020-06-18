# BERT with MulitGPUs
__Improving BERT Model to Support for running with multi GPUs__ <br />
__You can simply use codes selection what would you use for running !__ <br />

- Environment : Ubuntu 18.04, Tensorflow 1.14 CUDA 10.0, CUDNN 7.6.5
- Tested Model : BERT Multilingual Cased Model
- Dataset : SQuAD 1.1, 2.0 / KorQuAD 1.0, 2.1

<hr>

- *run_korquad* : running script for KorQuAD 2.x datasets <br />
- *_tf_multi* : use Tensorflow Mirror Strategy <br />
- *_hvd* : use Horovod Framework <br />

1. Tensorflow Mirrored Startegy API <br />
__Use run_squad_tf_multi.py and optimization_tf_multi.py__ <br />

2. Uber's Horovod Framework <br />
__Use run_squad_hvd.py and optimization_tf_multi.py__ <br />
