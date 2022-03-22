---
title: "IFT780: Réseaux de neurones"
collection: teaching
type: "Graduate course"
permalink: teaching/2021-spring-ift780
venue: "Université de Sherbrooke, Faculté des Sciences, Département d'informatique"
date: 2021-01-03
location: "Sherbrooke, QC"
---

**Local**: D3−2040 \
**Périodes de cours**:  Lundi 15:30−16:20, Mardi 15:30−17:20

Objectifs du cours
======
**Apprentissage supervisé par réseaux de neurones** : classification et régression avec réseaux à propagation avant et prédiction de cibles. **Réseaux de neurones classiques** : perceptron multi-couches et régression logistique. **Réseaux à convolution et architectures profondes ("deep learning") modernes** : VGG, InceptionNet, ResNet, UNet, etc. **Applications à l'imagerie** : reconnaissance, segmentation, localisation, transfert de style, etc. **Réseaux de neurones récurrents et applications à l'analyse de texte et d'images. Modèles génératifs adversaires et réseaux de neurones non-supervisés** : auto-encodeurs et auto-encodeurs variationnels. **Bonnes pratiques** : transfert d'entrainement, augmentation de données, normalisation, méthodes d'entrainement modernes, visualisation. **Concepts avancés**: modèles d'attention, autoML, compression, convolution dilatées.

Méthode pédagogique
======


|    | Thème                                                               | Slides                                     | Lectures: |
|----|---------------------------------------------------------------------|--------------------------------------------|
| 0  | Présentation                                                        | [PPTX](/files/ift780/00_presentation.pptx) |                                             |
| 1  | Concepts de base                                                    | [PPTX](/files/ift780/01_MLP.pptx)          | [[9]](#9) : 6.1, 6.2, 6.3, 6.5, [[45]](#27) |
| 2  | Réseaux à convolution                                               | [PPTX](/files/ift780/02_CNN.pptx)          | [[21]](#21) : 9.0 à 9.5 ; [[27]](#27) |
| 3  | Réseaux à convolution avancés et architectures convolutives modernes| [PPTX](/files/ift780/03_CNN_avance.pptx)   | Réseaux à convolutions : [[27]](#27) [[26]](#26) [[22]](#22) [[45]](#45) [[50]](#50) [[43]](#43) [[46]](#46) [[17]](#17) [[20]](#20) [[19]](#19) |
| 4  | Segmentation et localisation                                        | [PDF](/files/ift780/04_segmentation_localisation.pdf)   | Segmentation et localisation : [[48]](#48) [[29]](#29) [[1]](#1) [[42]](#42) [[32]](#32) [[5]](#5) [[23]](#23) [[6]](#6) [[34]](#34) [[14]](#14) [[13]](#13) [[41]](#41) [[39]](#39) [[40]](#40) [[28]](#28) [[16]](#16) |
| 5  | Matériel et bibliothèques de code                                   | [PDF](/files/ift780/05_materiel.pdf)       |           |
| 6  | Considérations pratiques                                            |                                            |           |
| 7  | Réseaux récurrents, attention et transformers                       | [PDF](/files/ift780/07_reseaux_recurrents.pdf) | Réseaux récurrents [[31]](#31) [[18]](#18) [[8]](#8) Attention : [[2]](#2) [[30]](#30) [[49]](#49) [[7]](#7) Transformers : [[47]](#47) [[11]](#11) [[37]](#37) [[38]](#38) [[4]](#4)|
| 8  | Modèles génératifs                                                  | [PDF](/files/ift780/08_modeles_generatifs.pdf) | Autoencodeurs : [[25]](#25) [[35]](#35) [[44]](#44) [[12]](#12) GANs : [[15]](#15) [[33]](#33) [[36]](#36) [[3]](#3) [[24]](#24) |
| 9  | Visualisation                                                       |                                            |           |
| 10 | Optimisation d’hyper-paramètres                                     |                                            |           |

Le plan de cours complet est disponible ici: [plan de cours](/files/ift780/ift780.pdf)

Travaux pratiques
======

|   | Nom                                      | Fichiers | Énoncé |
|---|------------------------------------------|----------|--------|
| 0 | Mise en place                            |                                      | [PPTX](/files/ift780/00_TP.pptx) |
| 1 | Réseaux de neurones pleinement connectés | [TP1.zip](/files/ift780/TP1/TP1.zip) | [PDF](/files/ift780/TP1/IFT780_TP1.pdf) |
| 2 | Réseaux de neurones convolutifs          | [TP2.zip](/files/ift780/TP2/TP2.zip) | [PDF](/files/ift780/TP2/IFT780_TP2.pdf) |
| 3 | Segmentation cardiaque                   | Voir Turnin | [PDF](/files/ift780/TP3/IFT780_TP3.pdf) |

Ressources
======
Il n'est absolument pas nécessaire de consulter des ressources additionnelles aux diapositives présentées dans le cours en assistant aux séances. Par contre, si vous souhaitez consulter les livres sur lequel le cours est basé:

[[21]](#21) Deep Learning - Ian J. Goodfellow, Yoshua Bengio and Aaron Courville, MIT Press, 2016 \
[[9]](#9) Pattern recognition and machine learning - Christopher M. Bishop, Springer, 2006

De plus, le livre suivant est très complet et pertinent pour les gens ayant un _background_ moins mathématique:

[[51]](#51) Mathematics for Machine Learning - M. Deisenroth, A. Faisal, and C. Ong, Cambridge University Press, 2020

Ces livres sont disponibles à la bibliothèque du Frère Théode et sur commande à la coop de l'Université de Sherbrooke. [[21]](#21) et [[9]](#9) sont aussi disponibles en ligne.

Références
======
[[1]<a name="1"></a> BADRINARAYANAN, VIJAY AND KENDALL, ALEX AND CIPOLLA, ROBERTO : Segnet : A deep convolutional encoderdecoder architecture for image segmentation. IEEE transactions on pattern analysis and machine intelligence, 39(12):2481–2495, 2017](https://arxiv.org/pdf/1511.00561.pdf)

[[2]<a name="2"></a> BAHDANAU, DZMITRY AND CHO, KYUNGHYUN AND BENGIO, YOSHUA : Neural machine translation by jointly learning to align and translate. arXiv preprint arXiv :1409.0473, 2014.](https://arxiv.org/pdf/1409.0473.pdf)

[[3]<a name="3"></a> BROCK, ANDREW AND DONAHUE, JEFF AND SIMONYAN, KAREN : Large scale GAN training for high fidelity natural image synthesis. arXiv preprint arXiv :1809.11096, 2018.](https://arxiv.org/pdf/1809.11096.pdf&org=deepmind)

[[4]<a name="4"></a> BROWN, TOM B AND MANN, BENJAMIN AND RYDER, NICK AND SUBBIAH, MELANIE AND KAPLAN, JARED AND DHARIWAL, PRAFULLA AND NEELAKANTAN, ARVIND AND SHYAM, PRANAV AND SASTRY, GIRISH AND ASKELL, AMANDA AND OTHERS : Language models are few-shot learners. arXiv preprint arXiv :2005.14165, 2020.](https://arxiv.org/pdf/2005.14165.pdf)

[[5]<a name="5"></a> ÇIÇEK, ÖZGÜN AND ABDULKADIR, AHMED AND LIENKAMP, SOEREN S AND BROX, THOMAS AND RONNEBERGER, OLAF : 3D U-Net : learning dense volumetric segmentation from sparse annotation. In International conference on medical image computing and computer-assisted intervention, pages 424–432. Springer, 2016.](https://arxiv.org/pdf/1606.06650.pdf)

[[6]<a name="6"></a> CHEN, LIANG-CHIEH AND PAPANDREOU, GEORGE AND KOKKINOS, IASONAS AND MURPHY, KEVIN AND YUILLE, ALAN L : Deeplab : Semantic image segmentation with deep convolutional nets, atrous convolution, and fully connected crfs. IEEE transactions on pattern analysis and machine intelligence, 40(4):834–848, 2017.](https://arxiv.org/pdf/1606.00915.pdf)

[[7]<a name="7"></a> CHENG, JIANPENG AND DONG, LI AND LAPATA, MIRELLA : Long short-term memory-networks for machine reading. arXiv preprint arXiv :1601.06733, 2016.](https://arxiv.org/pdf/1601.06733.pdf)

[[8]<a name="8"></a> CHO, KYUNGHYUN AND VAN MERRIËNBOER, BART AND GULCEHRE, CAGLAR AND BAHDANAU, DZMITRY AND BOUGARES, FETHI AND SCHWENK, HOLGER AND BENGIO, YOSHUA : Learning phrase representations using RNN encoderdecoder for statistical machine translation. arXiv preprint arXiv :1406.1078, 2014.](Learning phrase representations using RNN encoderdecoder for statistical machine translation)

[[9]<a name="9"></a> CHRISTOPHER M. BISHOP : Pattern Recognition and Machine Learning (Information Science and Statistics). SpringerVerlag, 2006.](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf)

[10]<a name="10"></a> CIREGAN, DAN AND MEIER, UELI AND SCHMIDHUBER, JÜRGEN : Multi-column deep neural networks for image classification. In 2012 IEEE conference on computer vision and pattern recognition, pages 3642–3649. IEEE, 2012.

[11]<a name="11"></a> DEVLIN, JACOB AND CHANG, MING-WEI AND LEE, KENTON AND TOUTANOVA, KRISTINA : Bert : Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv :1810.04805, 2018.

[12]<a name="12"></a> DOERSCH, CARL : Tutorial on variational autoencoders. arXiv preprint arXiv :1606.05908, 2016.

[13]<a name="13"></a> GIRSHICK, ROSS : Fast r-cnn. In Proceedings of the IEEE international conference on computer vision, pages 1440–1448, 2015.

[14]<a name="14"></a> GIRSHICK, ROSS AND DONAHUE, JEFF AND DARRELL, TREVOR AND MALIK, JITENDRA : Rich feature hierarchies for accurate object detection and semantic segmentation. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 580–587, 2014.

[15]<a name="15"></a> GOODFELLOW, IAN AND POUGET-ABADIE, JEAN AND MIRZA, MEHDI AND XU, BING AND WARDE-FARLEY, DAVID AND OZAIR, SHERJIL AND COURVILLE, AARON AND BENGIO, YOSHUA : Generative adversarial nets. Advances in neural information processing systems, 27, 2014.

[16]<a name="16"></a> HE, KAIMING AND GKIOXARI, GEORGIA AND DOLLÁR, PIOTR AND GIRSHICK, ROSS : Mask r-cnn. In Proceedings of the IEEE international conference on computer vision, pages 2961–2969, 2017.

[17]<a name="17"></a> HE, KAIMING AND ZHANG, XIANGYU AND REN, SHAOQING AND SUN, JIAN : Deep residual learning for image recognition. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 770–778, 2016.

[18]<a name="18"></a> HOCHREITER, SEPP AND SCHMIDHUBER, JÜRGEN : Long short-term memory. Neural computation, 9(8):1735–1780, 1997.

[19]<a name="19"></a> HOWARD, ANDREW G AND ZHU, MENGLONG AND CHEN, BO AND KALENICHENKO, DMITRY AND WANG, WEIJUN AND WEYAND, TOBIAS AND ANDREETTO, MARCO AND ADAM, HARTWIG : Mobilenets : Efficient convolutional neural networks for mobile vision applications. arXiv preprint arXiv :1704.04861, 2017.

[20]<a name="20"></a> HUANG, GAO AND LIU, ZHUANG AND VAN DER MAATEN, LAURENS AND WEINBERGER, KILIAN Q : Densely connected convolutional networks. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 4700–4708, 2017.

[[21]<a name="21"></a> IAN GOODFELLOW, YOSHUA BENGIO ET AARON COURVILLE : Deep Learning. MIT Press, 2016.](http://www.deeplearningbook.org)

[22]<a name="22"></a> IOFFE, SERGEY AND SZEGEDY, CHRISTIAN : Batch normalization : Accelerating deep network training by reducing internal covariate shift. In International conference on machine learning, pages 448–456. PMLR, 2015.

[23]<a name="23"></a> ISENSEE, FABIAN AND JAEGER, PAUL F AND KOHL, SIMON AA AND PETERSEN, JENS AND MAIER-HEIN, KLAUS H : nnU-Net : a self-configuring method for deep learning-based biomedical image segmentation. Nature methods, 18(2):203–211, 2021.

[24]<a name="24"></a> KARRAS, TERO AND LAINE, SAMULI AND AILA, TIMO : A style-based generator architecture for generative adversarial networks. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 4401–4410, 2019.

[25]<a name="25"></a> KINGMA, DIEDERIK P AND WELLING, MAX : Auto-encoding variational bayes. arXiv preprint arXiv :1312.6114, 2013.

[26]<a name="26"></a> KRIZHEVSKY, ALEX AND SUTSKEVER, ILYA AND HINTON, GEOFFREY E : Imagenet classification with deep convolutional neural networks. Advances in neural information processing systems, 25:1097–1105, 2012.

[[27]<a name="27"></a> LECUN, YANN AND BOTTOU, LÉON AND BENGIO, YOSHUA AND HAFFNER, PATRICK : Gradient-based learning applied to document recognition. Proceedings of the IEEE, 86(11):2278–2324, 1998.](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)

[28]<a name="28"></a> LIU, WEI AND ANGUELOV, DRAGOMIR AND ERHAN, DUMITRU AND SZEGEDY, CHRISTIAN AND REED, SCOTT AND FU, CHENG-YANG AND BERG, ALEXANDER C : Ssd : Single shot multibox detector. In European conference on computer vision, pages 21–37. Springer, 2016.

[29]<a name="29"></a> LONG, JONATHAN AND SHELHAMER, EVAN AND DARRELL, TREVOR : Fully convolutional networks for semantic segmentation. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 3431–3440, 2015.

[30]<a name="30"></a> LUONG, MINH-THANG AND PHAM, HIEU AND MANNING, CHRISTOPHER D : Effective approaches to attention-based neural machine translation. arXiv preprint arXiv :1508.04025, 2015.

[31]<a name="31"></a> MIKOLOV, TOMAS AND CHEN, KAI AND CORRADO, GREG AND DEAN, JEFFREY : Efficient estimation of word representations in vector space. arXiv preprint arXiv :1301.3781, 2013.

[32]<a name="32"></a> MILLETARI, FAUSTO AND NAVAB, NASSIR AND AHMADI, SEYED-AHMAD : V-net : Fully convolutional neural networks for volumetric medical image segmentation. In 2016 fourth international conference on 3D vision (3DV), pages 565–571. IEEE, 2016.

[33]<a name="33"></a> MIRZA, MEHDI AND OSINDERO, SIMON : Conditional generative adversarial nets. arXiv preprint arXiv :1411.1784, 2014.

[34]<a name="34"></a> PASZKE, ADAM AND CHAURASIA, ABHISHEK AND KIM, SANGPIL AND CULURCIELLO, EUGENIO : Enet : A deep neural network architecture for real-time semantic segmentation. arXiv preprint arXiv :1606.02147, 2016.

[35]<a name="35"></a> PLAUT, ELAD : From principal subspaces to principal components with linear autoencoders. arXiv preprint arXiv :1804.10253, 2018.

[36]<a name="36"></a> RADFORD, ALEC AND METZ, LUKE AND CHINTALA, SOUMITH : Unsupervised representation learning with deep convolutional generative adversarial networks. arXiv preprint arXiv :1511.06434, 2015.

[37]<a name="37"></a> RADFORD, ALEC AND NARASIMHAN, KARTHIK AND SALIMA

[38]<a name="38"></a> RADFORD, ALEC AND WU, JEFFREY AND CHILD, REWON AND LUAN, DAVID AND AMODEI, DARIO AND SUTSKEVER, ILYA AND OTHERS : Language models are unsupervised multitask learners. OpenAI blog, 1(8):9, 2019.

[39]<a name="39"></a> REDMON, JOSEPH AND DIVVALA, SANTOSH AND GIRSHICK, ROSS AND FARHADI, ALI : You only look once : Unified, real-time object detection. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 779–788, 2016.

[40]<a name="40"></a> REDMON, JOSEPH AND FARHADI, ALI : YOLO9000 : better, faster, stronger. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 7263–7271, 2017.

[41]<a name="41"></a> REN, SHAOQING AND HE, KAIMING AND GIRSHICK, ROSS AND SUN, JIAN : Faster r-cnn : Towards real-time object detection with region proposal networks. Advances in neural information processing systems, 28:91–99, 2015.

[42]<a name="42"></a> RONNEBERGER, OLAF AND FISCHER, PHILIPP AND BROX, THOMAS : U-net : Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention, pages 234–241. Springer, 2015.

[43]<a name="43"></a> SIMONYAN, KAREN AND ZISSERMAN, ANDREW : Very deep convolutional networks for large-scale image recognition. arXiv preprint arXiv :1409.1556, 2014.

[44]<a name="44"></a> SOHN, KIHYUK AND LEE, HONGLAK AND YAN, XINCHEN : Learning structured output representation using deep conditional generative models. Advances in neural information processing systems, 28:3483–3491, 2015.

[[45]<a name="45"></a> SRIVASTAVA, NITISH AND HINTON, GEOFFREY AND KRIZHEVSKY, ALEX AND SUTSKEVER, ILYA AND SALAKHUTDINOV, RUSLAN : Dropout : a simple way to prevent neural networks from overfitting. The journal of machine learning research, 15(1):1929–1958, 2014.](https://www.cs.toronto.edu/~rsalakhu/papers/srivastava14a.pdf)

[46]<a name="46"></a> SZEGEDY, CHRISTIAN AND LIU, WEI AND JIA, YANGQING AND SERMANET, PIERRE AND REED, SCOTT AND ANGUELOV, DRAGOMIR AND ERHAN, DUMITRU AND VANHOUCKE, VINCENT AND RABINOVICH, ANDREW : Going deeper with convolutions. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 1–9, 2015.

[47]<a name="47"></a> VASWANI, ASHISH AND SHAZEER, NOAM AND PARMAR, NIKI AND USZKOREIT, JAKOB AND JONES, LLION AND GOMEZ, AIDAN N AND KAISER, ŁUKASZ AND POLOSUKHIN, ILLIA : Attention is all you need. In Advances in neural information processing systems, pages 5998–6008, 2017.

[48]<a name="48"></a> WANG, YI AND LUO, ZHIMING AND JODOIN, PIERRE-MARC : Interactive deep learning method for segmenting moving objects. Pattern Recognition Letters, 96:66–75, 2017. 

[49]<a name="49"></a> XU, KELVIN AND BA, JIMMY AND KIROS, RYAN AND CHO, KYUNGHYUN AND COURVILLE, AARON AND SALAKHUDINOV, RUSLAN AND ZEMEL, RICH AND BENGIO, YOSHUA : Show, attend and tell : Neural image caption generation with visual attention. In International conference on machine learning, pages 2048–2057. PMLR, 2015.

[50]<a name="50"></a> ZEILER, MATTHEW D AND FERGUS, ROB : Visualizing and understanding convolutional networks. In European conference on computer vision, pages 818–833. Springer, 2014.
