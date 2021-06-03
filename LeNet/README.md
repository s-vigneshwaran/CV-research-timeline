# Gradient-based learning applied to document recognition

### Y. Lecun, L. Bottou, Y. Bengio and P. Haffner, "Gradient-based learning applied to document recognition," in Proceedings of the IEEE, vol. 86, no. 11, pp. 2278-2324, Nov. 1998, doi: 10.1109/5.726791.

http://yann.lecun.com/exdb/publis/index.html#lecun-98

First and foremost, you might think why LeNet-5? Because according to the timeline image it was supposed to be the initial LeNet[Lecun, Y., Boser, B., Denker, J. S., Henderson, D., Howard, R. E., Hubbard, W., & Jackel, L. D. (1990). Handwritten digit recognition with a back-propagation network. In D. Touretzky (Ed.), Advances in Neural Information Processing Systems (NIPS 1989), Denver, CO (Vol. 2). Morgan Kaufmann]. 

But the point to note is that, LeNet is actually a progressive research conducted over a span of 8 years. So here is the timeline from Wikipedia[https://en.wikipedia.org/wiki/LeNet#Development_history]

| Year      | Work | Paper     |
| -- | -- | -- |
| 1989	      | Yann LeCun et al. proposed the original form of LeNet       | LeCun, Y.; Boser, B.; Denker, J. S.; Henderson, D.; Howard, R. E.; Hubbard, W. & Jackel, L. D. (1989). Backpropagation applied to handwritten zip code recognition. Neural Computation, 1(4):541-551.   |
|1989	|Yann LeCun proves that minimizing the number of free parameters in neural networks can enhance the generalization ability of neural networks. | LeCun, Y.(1989). Generalization and network design strategies. Technical Report CRG-TR-89-4, Department of Computer Science, University of Toronto.|
| 1990	| Their paper describes the application of backpropagation networks in handwritten digit recognition once again |	LeCun, Y.; Boser, B.; Denker, J. S.; Henderson, D.; Howard, R. E.; Hubbard, W. & Jackel, L. D. (1990). Handwritten digit recognition with a back-propagation network. Advances in Neural Information Processing Systems 2 (NIPS*89). |
| 1998	| They reviewed various methods applied to handwritten character recognition and compared them with standard handwritten digit recognition benchmarks. The results show that convolutional neural networks outperform all other models. |	LeCun, Y.; Bottou, L.; Bengio, Y. & Haffner, P. (1998). Gradient-based learning applied to document recognition.Proceedings of the IEEE. 86(11): 2278 - 2324.|

Even though the first LeNet paper was published in 1989, the real convolutional emergence was only because of LeNet-5. Hence, I feel that LeNet-5 is the landmark paper among all the others LeNet variants.

![Lenet Architecture](https://miro.medium.com/max/2625/1*1TI1aGBZ4dybR6__DI9dzA.png)

