# Image Caption Generator
A deep learning model that generates captions based on input images.

This notebook aims to generate realistic captions based on input images, using CNN as Image Model and RNN / LSTM as Language Model. The approach utilised here is that of an Encoder-Decoder Model, i.e, the Encoder model will combine both the encoded form of the image and the encoded form of the caption (text) and feed it to the Decoder model. We will train the part of the neural network that handles images and the part that handles languages separately, using images and sentences from separate training sets. This is because the merging of image features with text encodings to a later stage in the architecture is advantageous and can generate better quality captions with smaller layers than the inject architecture.

## Here are the outputs :

![image](https://user-images.githubusercontent.com/83628182/214152547-2173c3a8-5a63-4fb3-90f7-603ccae4012b.png)

![image](https://user-images.githubusercontent.com/83628182/214152667-6748cd4b-82e8-4b78-b96e-add11337510a.png)

![image](https://user-images.githubusercontent.com/83628182/214152688-41e9a58b-67f3-40d4-9ddc-c0e1d144114f.png)

![image](https://user-images.githubusercontent.com/83628182/214152698-4eca356f-5323-4f2a-9766-fbfb56d30c68.png)
