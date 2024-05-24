# fish_classification
içerisindeki veri seti kaggle içerisinde bulunan https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset 'dir. CNN içerisindeki MobileNet, ResNet, Vgg16 ve Inception mimarileri kullanılmıştır. Ayrıca bir de CNN tek başına kullanılarak başarısı ölçülmüştür. Validation'da alınan başarılar ise :

*MobileNet'te %94.14
*ResNet'te %99.61
*Vgg16' da %99.54
*Inception (GoogleNet)'te %99.00
CNN'de ise %74.03 'tür. Fakat mimarilerin hızları birbirlerinden oldukça farklı olabilmektedir. MobileNet, ResNet ve GoogleNet normal bir hızda çalışıp işlemleri ortalama 1.5 saatte bitirebilirken VGG16'da bu süre 4 saate kadar çıkmıştır. Test verileri de eklenerek son doğruluk oranları bulunup eklenecektir.
