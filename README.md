
# NLP Models

|    Date    |      Model      | Token Size |   #Params   | #Features | Inference GFLOPs | Training PFLOPs |
|------------|-----------------|------------|-------------|-----------|------------------|-----------------|
| 12/6/2017  | Transformer     |        512 | 65M         | 77M       | 54               |                 |
| 10/11/2018 | BERT Large      |        512 | 330M        | 230M      | 340              |                 |
| 02/15/2018 | ELMO            |            | 94M         |           |                  |                 |
| 06/11/2018 | GPT-1           |        512 | 110M        | 85M       | 96               |                 |
| 02/14/2019 | GPT-2           |       1024 | 1,500M      | 2,000M    | 3,400            |                 |
| 08/17/2019 | Megatron        |       1024 | 8,300M      | 4,700M    | 18,000           |                 |
| 02/13/2020 | Microsoft T-NLP |       1024 | 17,000M     | 5,700M    | 36,000           |                 |
| 05/28/2020 | GPT-3           |       2048 | 175,000M    | 63,000M   | 740,000          |                 |
| 06/30/2020 | GShard          |            | 600,000M    |           |                  |                 |
| 06/20/2020 | Baidu RecSys-C  |            | 2,000,000M  |           | ~O(0.1)          |                 |
| 06/20/2020 | Baidu RecSys-E  |            | 10,000,000M |           | ~O(0.1)          |                 |



# Computer Vision Models
| Date |           Model            | Input Resolution | #Params | Top-1 | Inference GFLOPs | Training PFLOPs |
|------|----------------------------|------------------|---------|-------|------------------|-----------------|
|      | ResNet50                   | 224 x 224        | 25.56M  | 76.50 |             8.19 |                 |
|      | ResNet152                  | 224 x 224        | 60.19M  | 78.30 |            23.05 |                 |
|      | DenseNet264                | 224 x 224        | 33.37M  | 78.00 |            11.54 |                 |
|      | ResNeXt152 (64x4d)         | 224 x 224        | 107.57M | 79.50 |            43.03 |                 |
|      | SENet154 (vd)              | 224 x 224        | 114.29M | 81.40 |            45.83 |                 |
|      | Fix_ResNeXt101(32x48d_wsl) | 320 x 320        | 456.20M | 86.30 |           354.23 |                 |
