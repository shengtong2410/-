# -
人工智能与神经网络导论期终考试 24210180056 盛童

1. 编程题选择了【第五题：变分贝叶斯识别垃圾邮件】和【第六题：预测用户对电影评级】
2. HMC.ipynb为第二题【HMC采样混合高斯分布】代码文件
2. BNN.ipynb为第五题代码文件
3. Movie.ipynb为第六题代码文件
4. 数据集文件说明
 - enron2.tar为第五题原始数据的压缩包；ml-100k为第六题原始数据的压缩包；
 - enron2由于文件结构问题，代码中读取时使用的是绝对路径；请解压缩原始数据后修改路径再运行；
 - ml-100k解压后的数据文件都在data文件夹中，代码中读取时使用的是相对路径；此外，data文件夹中的merge_data.csv为合并数据；data_processed为处理后数据；train_data与test_data为按照时间顺序切分的测试集和训练集；train_data_random与test_data_random为随机切分的测试集和训练集；vocab_dict.json文件为向量嵌入所需要的最大类别数字典。使用这些中间文件允许不从头开始运行代码。

