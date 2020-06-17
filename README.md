# Speed Detect

Attempt to the [commaai speed challenge](https://github.com/commaai/speedchallenge).

 - Extracted frames of the train video
 - Shuffled the dataset (yes, I am ignoring the dependency on previous frames)
 - Resize and Centre crop frames to size 224 (vgg16)
 - Use vgg16 pretrained on imagenet and add replace last two layers
 - Train!

