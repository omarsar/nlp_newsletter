# NLP-Overview, Facebook’s XNLI, ShaRC, AutoAugment, pair2vec, Iterated Amplification,…
*Welcome to the* *32nd* *Issue of the NLP Newsletter! Here is* *an overview of* *this week’s notable NLP* *and AI* *news**: enhancing conversational and dialogue AI systems; an AI safety technique that involves humans and machines working together; an overview of modern deep learning techniques applied to NLP, and much more.*

**On People…**  
Amazon researchers will be hosting their first workshop on *fact extraction and verification* at EMNLP 2018. Earlier this year, the team released a dataset called [FEVER](https://developer.amazon.com/blogs/alexa/post/d1b3f12f-165d-41d4-a61b-cf36d17a8926/public-release-of-fever-dataset-quickly-begins-to-pay-dividends) which contains 185,000 *assertions of facts* together with sentences from Wikipedia that either substantiate or refute those facts. Results from several teams will be discussed at the conference in the coming days — [Link](https://developer.amazon.com/blogs/alexa/post/eaed4d64-c7af-4587-8241-7a006db9b19b/amazon-helps-launch-workshop-on-automatic-fact-verification)

ShaRC is a new dataset that focuses on building end to end conversational question answering systems that support the *addition of background knowledge*, especially when the system tries to answer a more difficult question, where the answer is not directly in the text source — [Link](https://sharc-data.github.io/index.html)

Materials for the deep learning and reinforcement learning summer school carried out in Toronto are now available (videos available). The materials include topics such as *auto differentiation*, *interpretability*, and *language understanding* — [Link](http://videolectures.net/DLRLsummerschool2018_toronto/)

OpenAI proposes a new AI safety technique called *iterated amplification*. The idea is that we can specify complicated behaviors and goals and be able to generate training signals that go beyond the traditional rewards and labels used in supervised and reinforcement learning, respectively. The interesting part is that humans are able to coordinate with an AI system in a framework that is able to scale up to higher level tasks based on a sample of smaller subtasks that are based on human judgement — [Link](https://blog.openai.com/amplifying-ai-training/)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_4720B845A2153427E6AE920A53067C7E6FBF384E9F4A1783A46231D8187EB81E_1540800303471_image.png)


**On Education and Research…**  

[Elvis Saravia](https://twitter.com/omarsar0) and  [Soujanya Poria](https://github.com/soujanyaporia) release a project called [NLP-Overview](https://nlpoverview.com/) that is intended to help students and practitioners get a condensed *overview of modern deep learning techniques applied to NLP*, including theory, algorithms, applications, and state of the art results—[Link](https://github.com/omarsar/nlp_overview)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_4720B845A2153427E6AE920A53067C7E6FBF384E9F4A1783A46231D8187EB81E_1540796625537_Untitled.png)


[François Fleuret](https://twitter.com/francoisfleuret) makes available the materials used to teach the *introduction to deep learning course* given in the African Master’s of Machine Intelligence at [AIMS](https://twitter.com/AIMS_Next). The materials include topics such as computer vision, optimization, and generative models—[Link](https://fleuret.org/ammi-2018/)

Facebook and New York University released a dataset called XNLI which was created for *evaluating cross-lingual approaches* to natural language understanding (NLU). XNLI also includes baselines that can assist researchers to create systems that understand multiple languages — [Link](https://code.fb.com/ai-research/xlni/)

pair2vec is a method for learning word embedding pairs that represent background knowledge about their implied relationships. The method is able to obtain gains on the SQuaD 2.0 dataset and can also be incorporated into a *cross-sentence layer* of existing inference models such as BiDAF — [Link](https://arxiv.org/abs/1810.08854)

**On Code and Data…**  
[Priya Dwivedi](https://towardsdatascience.com/@priya.dwivedi) covers the *building blocks of a question answering* system build on top of [Stanford Question Answering Dataset (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/). She explains all the main components that are needed to build an effective QA system — from the embedding layer to the output layer — [Link](https://towardsdatascience.com/nlp-building-a-question-answering-model-ed0529a68c54)

[Mac Brennan](https://medium.com/@mac.brennan.90) provides a nice detailed post on how to build a *neural translation model with attention*. He discusses the conceptual understanding of the model and also provides a brief summary of how the model performed — [Link](https://medium.com/datadriveninvestor/neural-translation-model-95277838d17d)

![](https://cdn-images-1.medium.com/max/800/1*Fs_ffi0a_5rw_5WiDvfOZg.png)


The Facebook AI research team releases a more *efficient implementation of R-CNN and Mask R-CNN* using PyTorch 1.0. The modular implementations can be used for *instance segmentation* and *object detection* — [Link](https://github.com/facebookresearch/maskrcnn-benchmark)

![](https://github.com/facebookresearch/maskrcnn-benchmark/raw/master/demo/demo_e2e_mask_rcnn_X_101_32x8d_FPN_1x.png)


[William Wang](https://mobile.twitter.com/WilliamWangNLP) and colleagues release code and paper for tackling a *cross-lingual dialog state tracking problem* using a simple but very efficient framework. The framework is based on a transfer learning technique that automatically generates semantic annotations in different languages and is able to track user’s beliefs (this paper is published in EMNLP 2018) — [Link](https://github.com/wenhuchen/Cross-Lingual-NBT)

If you want to conduct computer vision (CV) projects and research here is a detailed list of reliable and *rare CV datasets* used in the field — [Link](https://hackernoon.com/rare-datasets-for-computer-vision-every-machine-learning-expert-must-work-with-2ddaf52ad862)

The TensorFlow team releases *AutoAugment* which consists of a series of modules provided on TFHub that allows researchers to train better image models with fewer data using *image augmentation tricks* — [Link](https://tfhub.dev/s?keywords=image_augmentation)

**On Industry…**  
IBM releases a dataset which includes information that can be leveraged to build more comprehensive QA systems based on *knowledge* and *reasoning* — [Link](https://github.com/IBM/sciqa-arcade198-dataset)

Duolingo announces their *new AI website* which contains research publications, open datasets, and AI careers — [Link](https://ai.duolingo.com/)

Baidu releases a new machine translation algorithm called Simultaneous Translation with Anticipation and Controllable Latency (STACL), which performs *simultaneous translation* using a technique called *controllable latency*. Controllable latency works by using machine learning to anticipate speaker’s next words instead of having to wait for a speaker to make a pause in their speech to carry out the translation — [Link](https://siliconangle.com/2018/10/23/baidu-created-worlds-first-simultaneous-translation-system/)

**Worthy Mentions…**  
An in-depth machine learning tutorial that introduces readers to a machine learning pipeline from scratch using PyTorch — [Link](https://github.com/Spandan-Madan/DeepLearningProject)

How to implement a recursive neural network using TensorFlow — [Link](https://www.datasciencecentral.com/profiles/blogs/recursive-not-recurrent-neural-nets-in-tensorflow)

A research group from Maastricht University develop a GAN-based algorithm to generate logos — [Link](https://arxiv.org/pdf/1810.10395.pdf)

