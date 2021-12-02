python neural_style/neural_style.py eval --content-image images\content-images\amber.jpg --model  saved_models\candy.pth  --output-image  output_candy.jpg --cuda 0


python neural_style/neural_style.py train --dataset D:\Desktop\data\COCO\tmp --style-image images\style-images\candy.jpg --save-model-dir my_models --epochs 2 --cuda 0