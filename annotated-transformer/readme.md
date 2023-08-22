这个项目是网上大多数人推荐的Transformer写的比较好的一个项目，目前没有细看，因为我关注的是ViT，只有编码器没有解码器，所以转而去看timm库的ViT了。

在模型结构这里有一个关系要理清楚：
Encoder > Encoder Layer(要堆叠的整个框) > Sub Layer(multiAttention、FFN) >