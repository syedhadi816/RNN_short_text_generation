# RNN_short_text_generation
Character Level Language Model 

The main task of the character-level language model is to predict the next character given all previous characters in a sequence of data, i.e. generates text character by character. More formally, given a training sequence (x¹, … , x^T), the RNN uses the sequence of its output vectors (o¹, … , o^T) to obtain a sequence of predictive distributions P(x^t/x^{t-1}) = softmax(o^t). These models form the basis of predictive text completion in cell phones!

![alt text](https://images.samsung.com/is/image/samsung/assets/uk/support/mobile-devices/how-can-i-personalise-and-turn-predictive-text-on-and-off-on-my-samsung-galaxy-device/images/1-uk-how-can-i-personalise-and-turn-predictive-text-on-and-off.png)
Image Source: Samsung

