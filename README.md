# BasicEncoderDecoder
## Motivation
This is a basic encoded decoder I made to get a better understanding of how encoder-decoders work. I also wanted to better understand how changes in loss function, learning rate, model architecture, number of raining trials, etc effect the outcome of a model. This was a visual way to do that. Anyway, this and tinkering took me about three hours, and I learned alot from it.

## Specifications
I use a basic MLP arcitecture with 4 hidden layers. The loss function is a Smooth L1 Loss, which is just the absolute distance betwena the predicted and desired outputs, but smoothed by 0 so it is differentiable. I used Adam for the optimizer with the standard 0.0003 learning rate.
