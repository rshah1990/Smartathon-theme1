## Smartathon Theme 1

## Documentation Link: https://github.com/rshah1990/Smartathon-theme1/blob/main/Hackathon.pdf

## Weights File: https://drive.google.com/file/d/1I0xjJqLrDlgxiieXmQA7j8jSzoaLTogI/view?usp=share_link

## Project Overview 

<ul>
<li>We have used YOLO V5 pretrained model trained on COCO dataset as starting point. We have retrained model on our data set to reduce training time & more accurate model </li>
<li>We have tried data augmentation to reduce class imbalance </li>
<li>Used customized stratified train test split to avoid data bias </li>
<li>Split 80-20% of class with minimum number of samples , if number of samples is 1 than move it into training </li>
<li>For next class identify how many classes is already available in training (since its multilabel ) & how many ideally should be based on 80-20 split </li>
<li>We randomly sample those many numbers of rows from the training if number of classes less than expected else don’t sample anything move everything to test set</li>
<li>Experiment tracking using weights and biases </li>
<li>Different technique tried to improve data Quality</li>
</ul>
