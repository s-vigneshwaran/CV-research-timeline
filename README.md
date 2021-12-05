# Computer Vision Timeline (Repo under development)

### _Re-Implementation of landmark Computer Vision Papers_

![Image](https://www.researchgate.net/profile/Lokesh-Sharma-14/publication/337554353/figure/fig1/AS:834097404456962@1575875726745/Timeline-of-related-research.png)

I came across this image when I was searching about the history of Convolutional Neural Networks. I started reading the papers of these models in the chronological order.

When I was reading, I realized that the papers are really the building blocks of current day's Computer Vision. One more point to note is that the early cnn models which were implemented originally were such a pain as there were no frameworks or any sort of it. Everything was coded from scratch.

But with the help of modern frameworks its just a matter of couple of minutes to implement the architectures. So thats my motivation here. Reading and implementing landmark architectures is really a good way of understanding the trends in the field.

## How are these implemented?

-   Python Notebooks
-   Tensorflow
-   Tried to use Sequential models as much as possible as the objective is to keep it simple. But Functional APIs and Sub Classes are also used for some complicated models.
-   Datasets mentioned in the paper are used and not datasets like mnist or cifar.
-   Pretty much every model after LeNet used huge datasets. So only the architecture is implemented and are not trained.
-   For models which are not trained, transfer learning notebooks are implemented(for certain papers only)
-   Data Generators are implemented to match the input dimensions as mentioned on the original paper
-   Additional Pre-Processing techniques like color-correction, noise reduction are not implemented

## License

MIT
