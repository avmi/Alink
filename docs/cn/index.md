# Alink 算法组件列表
## 批流组件

### 数据源
* [Ak文件数据源(batch)](operator/source/AkSourceBatchOp.md)
* [Ak文件数据源(stream)](operator/source/AkSourceStreamOp.md)
* [Catalog数据库数据源(batch)](operator/source/CatalogSourceBatchOp.md)
* [Catalog数据库数据源(stream)](operator/source/CatalogSourceStreamOp.md)
* [Csv文件数据源(batch)](operator/source/CsvSourceBatchOp.md)
* [Csv文件数据源(stream)](operator/source/CsvSourceStreamOp.md)
* [KafkaSourceStreamOp](operator/source/KafkaSourceStreamOp.md)
* [LibSvm文件数据源(batch)](operator/source/LibSvmSourceBatchOp.md)
* [LibSvm文件数据源(stream)](operator/source/LibSvmSourceStreamOp.md)
* [内存数据源(batch)](operator/source/MemSourceBatchOp.md)
* [内存数据源(stream)](operator/source/MemSourceStreamOp.md)
* [数值队列数据源(batch)](operator/source/NumSeqSourceBatchOp.md)
* [数值队列数据源(stream)](operator/source/NumSeqSourceStreamOp.md)
* [随机生成结构数据源(batch)](operator/source/RandomTableSourceBatchOp.md)
* [随机生成结构数据源(stream)](operator/source/RandomTableSourceStreamOp.md)
* [随机生成向量数据源(batch)](operator/source/RandomVectorSourceBatchOp.md)
* [随机生成向量数据源(stream)](operator/source/RandomVectorSourceStreamOp.md)
* [Table数据源(batch)](operator/source/TableSourceBatchOp.md)
* [Table数据源(stream)](operator/source/TableSourceStreamOp.md)
* [Text文件数据源(batch)](operator/source/TextSourceBatchOp.md)
* [Text文件数据源(stream)](operator/source/TextSourceStreamOp.md)
* [Tsv文件数据源(batch)](operator/source/TsvSourceBatchOp.md)
* [Tsv文件数据源(stream)](operator/source/TsvSourceStreamOp.md)

### 数据导出
* [Ak文件输出(batch)](operator/sink/AkSinkBatchOp.md)
* [Ak文件输出(stream)](operator/sink/AkSinkStreamOp.md)
* [Catalog数据表输出(batch)](operator/sink/CatalogSinkBatchOp.md)
* [Catalog数据表输出(stream)](operator/sink/CatalogSinkStreamOp.md)
* [Csv文件输出(batch)](operator/sink/CsvSinkBatchOp.md)
* [Csv文件输出(stream)](operator/sink/CsvSinkStreamOp.md)
* [KafkaSinkStreamOp](operator/sink/KafkaSinkStreamOp.md)
* [LibSvm文件输出(batch)](operator/sink/LibSvmSinkBatchOp.md)
* [LibSvm文件输出(stream)](operator/sink/LibSvmSinkStreamOp.md)
* [Text文件输出(batch)](operator/sink/TextSinkBatchOp.md)
* [Text文件输出(stream)](operator/sink/TextSinkStreamOp.md)
* [Tsv文件输出(batch)](operator/sink/TsvSinkBatchOp.md)
* [Tsv文件输出(stream)](operator/sink/TsvSinkStreamOp.md)

### 数据处理
* [添加id列(batch)](operator/dataproc/AppendIdBatchOp.md)
* [前N个数(batch)](operator/dataproc/FirstNBatchOp.md)
* [缺失值填充批预测](operator/dataproc/ImputerPredictBatchOp.md)
* [缺失值填充流预测](operator/dataproc/ImputerPredictStreamOp.md)
* [缺失值填充训练](operator/dataproc/ImputerTrainBatchOp.md)
* [IndexToString预测(batch)](operator/dataproc/IndexToStringPredictBatchOp.md)
* [IndexToString预测(stream)](operator/dataproc/IndexToStringPredictStreamOp.md)
* [Json值抽取(batch)](operator/dataproc/JsonValueBatchOp.md)
* [Json值抽取(stream)](operator/dataproc/JsonValueStreamOp.md)
* [KV转换(batch)](operator/dataproc/KeyToValueBatchOp.md)
* [KV转换(stream)](operator/dataproc/KeyToValueStreamOp.md)
* [KeyToValuesBatchOp](operator/dataproc/KeyToValuesBatchOp.md)
* [KeyToValuesDynamicStreamOp](operator/dataproc/KeyToValuesDynamicStreamOp.md)
* [KeyToValuesStreamOp](operator/dataproc/KeyToValuesStreamOp.md)
* [绝对值最大化批预测](operator/dataproc/MaxAbsScalerPredictBatchOp.md)
* [绝对值最大化流预测](operator/dataproc/MaxAbsScalerPredictStreamOp.md)
* [绝对值最大化训练](operator/dataproc/MaxAbsScalerTrainBatchOp.md)
* [归一化批预测](operator/dataproc/MinMaxScalerPredictBatchOp.md)
* [归一化流预测](operator/dataproc/MinMaxScalerPredictStreamOp.md)
* [归一化训练](operator/dataproc/MinMaxScalerTrainBatchOp.md)
* [MultiStringIndexer预测(batch)](operator/dataproc/MultiStringIndexerPredictBatchOp.md)
* [MultiStringIndexer预测(stream)](operator/dataproc/MultiStringIndexerPredictStreamOp.md)
* [MultiStringIndexer训练(batch)](operator/dataproc/MultiStringIndexerTrainBatchOp.md)
* [随机采样(batch)](operator/dataproc/SampleBatchOp.md)
* [随机采样(stream)](operator/dataproc/SampleStreamOp.md)
* [固定条数随机采样(batch)](operator/dataproc/SampleWithSizeBatchOp.md)
* [打乱数据顺序](operator/dataproc/ShuffleBatchOp.md)
* [数据拆分(batch)](operator/dataproc/SplitBatchOp.md)
* [数据拆分(stream)](operator/dataproc/SplitStreamOp.md)
* [标准化批预测](operator/dataproc/StandardScalerPredictBatchOp.md)
* [标准化流预测](operator/dataproc/StandardScalerPredictStreamOp.md)
* [标准化训练](operator/dataproc/StandardScalerTrainBatchOp.md)
* [分层随机采样(batch)](operator/dataproc/StratifiedSampleBatchOp.md)
* [分层随机采样(stream)](operator/dataproc/StratifiedSampleStreamOp.md)
* [固定条数分层随机采样(batch)](operator/dataproc/StratifiedSampleWithSizeBatchOp.md)
* [StringIndexer预测(batch)](operator/dataproc/StringIndexerPredictBatchOp.md)
* [StringIndexer预测(stream)](operator/dataproc/StringIndexerPredictStreamOp.md)
* [StringIndexer训练(batch)](operator/dataproc/StringIndexerTrainBatchOp.md)
* [加权随机采样(batch)](operator/dataproc/WeightSampleBatchOp.md)

#### 数据格式转换
* [列数据转csv(batch)](operator/dataproc/format/ColumnsToCsvBatchOp.md)
* [列数据转csv(stream)](operator/dataproc/format/ColumnsToCsvStreamOp.md)
* [列数据转json(batch)](operator/dataproc/format/ColumnsToJsonBatchOp.md)
* [列数据转json(stream)](operator/dataproc/format/ColumnsToJsonStreamOp.md)
* [列数据转kv(batch)](operator/dataproc/format/ColumnsToKvBatchOp.md)
* [列数据转kv(stream)](operator/dataproc/format/ColumnsToKvStreamOp.md)
* [列数据转三元组(batch)](operator/dataproc/format/ColumnsToTripleBatchOp.md)
* [列数据转三元组(stream)](operator/dataproc/format/ColumnsToTripleStreamOp.md)
* [列数据转向量(batch)](operator/dataproc/format/ColumnsToVectorBatchOp.md)
* [列数据转向量(stream)](operator/dataproc/format/ColumnsToVectorStreamOp.md)
* [csv转列数据(batch)](operator/dataproc/format/CsvToColumnsBatchOp.md)
* [csv转列数据(stream)](operator/dataproc/format/CsvToColumnsStreamOp.md)
* [csv转json(batch)](operator/dataproc/format/CsvToJsonBatchOp.md)
* [csv转json(stream)](operator/dataproc/format/CsvToJsonStreamOp.md)
* [csv转kv(batch)](operator/dataproc/format/CsvToKvBatchOp.md)
* [csv转kv(stream)](operator/dataproc/format/CsvToKvStreamOp.md)
* [csv转三元组(batch)](operator/dataproc/format/CsvToTripleBatchOp.md)
* [csv转三元组(stream)](operator/dataproc/format/CsvToTripleStreamOp.md)
* [csv转向量(batch)](operator/dataproc/format/CsvToVectorBatchOp.md)
* [csv转向量(stream)](operator/dataproc/format/CsvToVectorStreamOp.md)
* [json转列数据(batch)](operator/dataproc/format/JsonToColumnsBatchOp.md)
* [json转列数据(stream)](operator/dataproc/format/JsonToColumnsStreamOp.md)
* [json转csv(batch)](operator/dataproc/format/JsonToCsvBatchOp.md)
* [json转csv(stream)](operator/dataproc/format/JsonToCsvStreamOp.md)
* [json转kv(batch)](operator/dataproc/format/JsonToKvBatchOp.md)
* [json转kv(stream)](operator/dataproc/format/JsonToKvStreamOp.md)
* [json转三元组(batch)](operator/dataproc/format/JsonToTripleBatchOp.md)
* [json转三元组(stream)](operator/dataproc/format/JsonToTripleStreamOp.md)
* [json转向量(batch)](operator/dataproc/format/JsonToVectorBatchOp.md)
* [json转向量(stream)](operator/dataproc/format/JsonToVectorStreamOp.md)
* [kv转列数据(batch)](operator/dataproc/format/KvToColumnsBatchOp.md)
* [kv转列数据(stream)](operator/dataproc/format/KvToColumnsStreamOp.md)
* [kv转csv(batch)](operator/dataproc/format/KvToCsvBatchOp.md)
* [kv转csv(stream)](operator/dataproc/format/KvToCsvStreamOp.md)
* [kv转json(batch)](operator/dataproc/format/KvToJsonBatchOp.md)
* [kv转json(stream)](operator/dataproc/format/KvToJsonStreamOp.md)
* [kv转三元组(batch)](operator/dataproc/format/KvToTripleBatchOp.md)
* [kv转三元组(stream)](operator/dataproc/format/KvToTripleStreamOp.md)
* [kv转向量(batch)](operator/dataproc/format/KvToVectorBatchOp.md)
* [kv转向量(stream)](operator/dataproc/format/KvToVectorStreamOp.md)
* [三元组转列数据(batch)](operator/dataproc/format/TripleToColumnsBatchOp.md)
* [三元组转csv(batch)](operator/dataproc/format/TripleToCsvBatchOp.md)
* [三元组转json(batch)](operator/dataproc/format/TripleToJsonBatchOp.md)
* [三元组转kv(batch)](operator/dataproc/format/TripleToKvBatchOp.md)
* [三元组转向量(batch)](operator/dataproc/format/TripleToVectorBatchOp.md)
* [向量转列数据(batch)](operator/dataproc/format/VectorToColumnsBatchOp.md)
* [向量转列数据(stream)](operator/dataproc/format/VectorToColumnsStreamOp.md)
* [向量转csv(batch)](operator/dataproc/format/VectorToCsvBatchOp.md)
* [向量转csv(stream)](operator/dataproc/format/VectorToCsvStreamOp.md)
* [向量转json(batch)](operator/dataproc/format/VectorToJsonBatchOp.md)
* [向量转json(stream)](operator/dataproc/format/VectorToJsonStreamOp.md)
* [向量转kv(batch)](operator/dataproc/format/VectorToKvBatchOp.md)
* [向量转kv(stream)](operator/dataproc/format/VectorToKvStreamOp.md)
* [向量转三元组(batch)](operator/dataproc/format/VectorToTripleBatchOp.md)
* [向量转三元组(stream)](operator/dataproc/format/VectorToTripleStreamOp.md)

#### 向量
* [向量聚合(batch)](operator/dataproc/vector/VectorAssemblerBatchOp.md)
* [向量聚合(stream)](operator/dataproc/vector/VectorAssemblerStreamOp.md)
* [向量元素依次相乘(batch)](operator/dataproc/vector/VectorElementwiseProductBatchOp.md)
* [向量元素依次相乘(stream)](operator/dataproc/vector/VectorElementwiseProductStreamOp.md)
* [向量缺失值填充预测(batch)](operator/dataproc/vector/VectorImputerPredictBatchOp.md)
* [向量缺失值填充预测(stream)](operator/dataproc/vector/VectorImputerPredictStreamOp.md)
* [向量缺失值填充训练](operator/dataproc/vector/VectorImputerTrainBatchOp.md)
* [向量元素两两相乘(batch)](operator/dataproc/vector/VectorInteractionBatchOp.md)
* [向量元素两两相乘(stream)](operator/dataproc/vector/VectorInteractionStreamOp.md)
* [向量绝对值最大化预测(batch)](operator/dataproc/vector/VectorMaxAbsScalerPredictBatchOp.md)
* [向量绝对值最大化预测(stream)](operator/dataproc/vector/VectorMaxAbsScalerPredictStreamOp.md)
* [向量绝对值最大化训练](operator/dataproc/vector/VectorMaxAbsScalerTrainBatchOp.md)
* [向量归一化预测(batch)](operator/dataproc/vector/VectorMinMaxScalerPredictBatchOp.md)
* [向量归一化预测(stream)](operator/dataproc/vector/VectorMinMaxScalerPredictStreamOp.md)
* [向量归一化训练](operator/dataproc/vector/VectorMinMaxScalerTrainBatchOp.md)
* [向量标准化(batch)](operator/dataproc/vector/VectorNormalizeBatchOp.md)
* [向量标准化(stream)](operator/dataproc/vector/VectorNormalizeStreamOp.md)
* [向量多项式展开(batch)](operator/dataproc/vector/VectorPolynomialExpandBatchOp.md)
* [向量多项式展开(stream)](operator/dataproc/vector/VectorPolynomialExpandStreamOp.md)
* [向量长度检验(batch)](operator/dataproc/vector/VectorSizeHintBatchOp.md)
* [向量长度检验(stream)](operator/dataproc/vector/VectorSizeHintStreamOp.md)
* [向量切片(batch)](operator/dataproc/vector/VectorSliceBatchOp.md)
* [向量切片(stream)](operator/dataproc/vector/VectorSliceStreamOp.md)
* [向量标准化预测(batch)](operator/dataproc/vector/VectorStandardScalerPredictBatchOp.md)
* [向量标准化预测(stream)](operator/dataproc/vector/VectorStandardScalerPredictStreamOp.md)
* [向量标准化训练](operator/dataproc/vector/VectorStandardScalerTrainBatchOp.md)

### SQL
* [SQL操作：As(batch)](operator/sql/AsBatchOp.md)
* [SQL操作：As(stream)](operator/sql/AsStreamOp.md)
* [SQL操作：Distinct(batch)](operator/sql/DistinctBatchOp.md)
* [SQL操作：Filter(batch)](operator/sql/FilterBatchOp.md)
* [SQL操作：Filter(stream)](operator/sql/FilterStreamOp.md)
* [SQL操作：FullOuterJoin(batch)](operator/sql/FullOuterJoinBatchOp.md)
* [SQL操作：GroupBy(batch)](operator/sql/GroupByBatchOp.md)
* [SQL操作：IntersectAll(batch)](operator/sql/IntersectAllBatchOp.md)
* [SQL操作：Intersect(batch)](operator/sql/IntersectBatchOp.md)
* [SQL操作：Join(batch)](operator/sql/JoinBatchOp.md)
* [SQL操作：LeftOuterJoin(batch)](operator/sql/LeftOuterJoinBatchOp.md)
* [SQL操作：MinusAll(batch)](operator/sql/MinusAllBatchOp.md)
* [SQL操作：Minus(batch)](operator/sql/MinusBatchOp.md)
* [SQL操作：OrderBy(batch)](operator/sql/OrderByBatchOp.md)
* [SQL操作：RightOuterJoin(batch)](operator/sql/RightOuterJoinBatchOp.md)
* [SQL操作：Select(batch)](operator/sql/SelectBatchOp.md)
* [SQL操作：Select(stream)](operator/sql/SelectStreamOp.md)
* [SQL操作：UnionAll(batch)](operator/sql/UnionAllBatchOp.md)
* [SQL操作：UnionAll(stream)](operator/sql/UnionAllStreamOp.md)
* [SQL操作：Union(batch)](operator/sql/UnionBatchOp.md)
* [SQL操作：Where(batch)](operator/sql/WhereBatchOp.md)
* [SQL操作：Where(stream)](operator/sql/WhereStreamOp.md)
* [SQL操作：WindowGroupBy(stream)](operator/sql/WindowGroupByStreamOp.md)

### 特征工程
* [二值化(batch)](operator/feature/BinarizerBatchOp.md)
* [二值化(stream)](operator/feature/BinarizerStreamOp.md)
* [分桶(batch)](operator/feature/BucketizerBatchOp.md)
* [分桶(stream)](operator/feature/BucketizerStreamOp.md)
* [卡放选择器(batch)](operator/feature/ChiSqSelectorBatchOp.md)
* [离散余弦变换(batch)](operator/feature/DCTBatchOp.md)
* [离散余弦变换(stream)](operator/feature/DCTStreamOp.md)
* [等宽离散化预测(batch)](operator/feature/EqualWidthDiscretizerPredictBatchOp.md)
* [等宽离散化预测(stream)](operator/feature/EqualWidthDiscretizerPredictStreamOp.md)
* [等宽离散化训练](operator/feature/EqualWidthDiscretizerTrainBatchOp.md)
* [特征哈希(batch)](operator/feature/FeatureHasherBatchOp.md)
* [特征哈希(stream)](operator/feature/FeatureHasherStreamOp.md)
* [独热编码预测(batch)](operator/feature/OneHotPredictBatchOp.md)
* [独热编码预测(stream)](operator/feature/OneHotPredictStreamOp.md)
* [独热编码训练](operator/feature/OneHotTrainBatchOp.md)
* [主成分分析预测(batch)](operator/feature/PcaPredictBatchOp.md)
* [主成分分析预测(stream)](operator/feature/PcaPredictStreamOp.md)
* [主成分分析训练(batch)](operator/feature/PcaTrainBatchOp.md)
* [分位数离散器预测(batch)](operator/feature/QuantileDiscretizerPredictBatchOp.md)
* [分位数离散器预测(stream)](operator/feature/QuantileDiscretizerPredictStreamOp.md)
* [分位数离散器训练(batch)](operator/feature/QuantileDiscretizerTrainBatchOp.md)
* [向量卡方选择器(batch)](operator/feature/VectorChiSqSelectorBatchOp.md)

### 文本
* [文本特征生成预测(batch)](operator/nlp/DocCountVectorizerPredictBatchOp.md)
* [文本特征生成预测(stream)](operator/nlp/DocCountVectorizerPredictStreamOp.md)
* [文本特征生成训练(batch)](operator/nlp/DocCountVectorizerTrainBatchOp.md)
* [文本哈希特征生成预测(batch)](operator/nlp/DocHashCountVectorizerPredictBatchOp.md)
* [文本哈希特征生成预测(stream)](operator/nlp/DocHashCountVectorizerPredictStreamOp.md)
* [文本哈希特征生成训练(batch)](operator/nlp/DocHashCountVectorizerTrainBatchOp.md)
* [文本词频统计(batch)](operator/nlp/DocWordCountBatchOp.md)
* [文本词频统计(stream)](operator/nlp/DocWordCountStreamOp.md)
* [关键词抽取(batch)](operator/nlp/KeywordsExtractionBatchOp.md)
* [关键词抽取(stream)](operator/nlp/KeywordsExtractionStreamOp.md)
* [NGram(batch)](operator/nlp/NGramBatchOp.md)
* [NGram(stream)](operator/nlp/NGramStreamOp.md)
* [RegexTokenizer(batch)](operator/nlp/RegexTokenizerBatchOp.md)
* [RegexTokenizer(stream)](operator/nlp/RegexTokenizerStreamOp.md)
* [分词(batch)](operator/nlp/SegmentBatchOp.md)
* [分词(stream)](operator/nlp/SegmentStreamOp.md)
* [停顿词过滤(batch)](operator/nlp/StopWordsRemoverBatchOp.md)
* [停顿词过滤(stream)](operator/nlp/StopWordsRemoverStreamOp.md)
* [文本分解(batch)](operator/nlp/TokenizerBatchOp.md)
* [文本分解(stream)](operator/nlp/TokenizerStreamOp.md)
* [Word2Vec预测(batch)](operator/nlp/Word2VecPredictBatchOp.md)
* [Word2Vec预测(stream)](operator/nlp/Word2VecPredictStreamOp.md)
* [Word2Vec训练](operator/nlp/Word2VecTrainBatchOp.md)
* [单词计数(batch)](operator/nlp/WordCountBatchOp.md)

### 统计分析
* [卡方检验(batch)](operator/statistics/ChiSquareTestBatchOp.md)
* [相关系数(batch)](operator/statistics/CorrelationBatchOp.md)
* [全表统计(batch)](operator/statistics/SummarizerBatchOp.md)
* [向量卡方检验(batch)](operator/statistics/VectorChiSquareTestBatchOp.md)
* [向量相关系数(batch)](operator/statistics/VectorCorrelationBatchOp.md)
* [向量全表统计(batch)](operator/statistics/VectorSummarizerBatchOp.md)

### 分类
* [C45决策树分类预测(batch)](operator/classification/C45PredictBatchOp.md)
* [C45决策树分类(stream)](operator/classification/C45PredictStreamOp.md)
* [C45决策树分类训练](operator/classification/C45TrainBatchOp.md)
* [Cart预测(batch)](operator/classification/CartPredictBatchOp.md)
* [Cart预测(stream)](operator/classification/CartPredictStreamOp.md)
* [Cart训练](operator/classification/CartTrainBatchOp.md)
* [决策树预测(batch)](operator/classification/DecisionTreePredictBatchOp.md)
* [决策树预测(stream)](operator/classification/DecisionTreePredictStreamOp.md)
* [决策树训练](operator/classification/DecisionTreeTrainBatchOp.md)
* [FM分类预测(batch)](operator/classification/FmClassifierPredictBatchOp.md)
* [FM分类预测(stream)](operator/classification/FmClassifierPredictStreamOp.md)
* [FM分类训练](operator/classification/FmClassifierTrainBatchOp.md)
* [GBDT分类器预测(batch)](operator/classification/GbdtPredictBatchOp.md)
* [GBDT分类器预测(stream)](operator/classification/GbdtPredictStreamOp.md)
* [GBDT分类器训练](operator/classification/GbdtTrainBatchOp.md)
* [Id3决策树分类预测(batch)](operator/classification/Id3PredictBatchOp.md)
* [Id3决策树分类预测(stream)](operator/classification/Id3PredictStreamOp.md)
* [Id3决策树分类训练](operator/classification/Id3TrainBatchOp.md)
* [最近邻分类预测(batch)](operator/classification/KnnPredictBatchOp.md)
* [最近邻分类训练(batch)](operator/classification/KnnTrainBatchOp.md)
* [线性支持向量机预测(batch)](operator/classification/LinearSvmPredictBatchOp.md)
* [线性支持向量机预测(stream)](operator/classification/LinearSvmPredictStreamOp.md)
* [线性支持向量机训练](operator/classification/LinearSvmTrainBatchOp.md)
* [逻辑回归预测(batch)](operator/classification/LogisticRegressionPredictBatchOp.md)
* [罗辑回归预测(stream)](operator/classification/LogisticRegressionPredictStreamOp.md)
* [逻辑回归训练](operator/classification/LogisticRegressionTrainBatchOp.md)
* [多层感知机分类预测(batch)](operator/classification/MultilayerPerceptronPredictBatchOp.md)
* [多层感知机分类预测(stream)](operator/classification/MultilayerPerceptronPredictStreamOp.md)
* [多层感知机分类训练](operator/classification/MultilayerPerceptronTrainBatchOp.md)
* [朴素贝叶斯预测(batch)](operator/classification/NaiveBayesPredictBatchOp.md)
* [朴素贝叶斯预测(stream)](operator/classification/NaiveBayesPredictStreamOp.md)
* [朴素贝叶斯文本分类预测(batch)](operator/classification/NaiveBayesTextPredictBatchOp.md)
* [朴素贝叶斯文本分类预测(stream)](operator/classification/NaiveBayesTextPredictStreamOp.md)
* [朴素贝叶斯文本分类训练](operator/classification/NaiveBayesTextTrainBatchOp.md)
* [朴素贝叶斯训练](operator/classification/NaiveBayesTrainBatchOp.md)
* [随机森林预测(batch)](operator/classification/RandomForestPredictBatchOp.md)
* [随机森林预测(stream)](operator/classification/RandomForestPredictStreamOp.md)
* [随机森林训练](operator/classification/RandomForestTrainBatchOp.md)
* [Softmax预测(batch)](operator/classification/SoftmaxPredictBatchOp.md)
* [Softmax预测(stream)](operator/classification/SoftmaxPredictStreamOp.md)
* [Softmax训练](operator/classification/SoftmaxTrainBatchOp.md)

### 回归
* [生存回归预测(batch)](operator/regression/AftSurvivalRegPredictBatchOp.md)
* [生存回归预测(stream)](operator/regression/AftSurvivalRegPredictStreamOp.md)
* [生存回归训练](operator/regression/AftSurvivalRegTrainBatchOp.md)
* [Cart回归预测(batch)](operator/regression/CartRegPredictBatchOp.md)
* [Cart回归预测(stream)](operator/regression/CartRegPredictStreamOp.md)
* [Cart回归训练(batch)](operator/regression/CartRegTrainBatchOp.md)
* [决策树回归预测(batch)](operator/regression/DecisionTreeRegPredictBatchOp.md)
* [决策树回归预测(stream)](operator/regression/DecisionTreeRegPredictStreamOp.md)
* [决策树回归训练(batch)](operator/regression/DecisionTreeRegTrainBatchOp.md)
* [FM回归预测(batch)](operator/regression/FmRegressorPredictBatchOp.md)
* [FM回归预测(stream)](operator/regression/FmRegressorPredictStreamOp.md)
* [FM回归训练(batch)](operator/regression/FmRegressorTrainBatchOp.md)
* [GBDT排序预测(stream)](operator/regression/GBRankPredictStreamOp.md)
* [GBDT回归预测(batch)](operator/regression/GbdtRegPredictBatchOp.md)
* [GBDT回归预测(stream)](operator/regression/GbdtRegPredictStreamOp.md)
* [GBDT回归训练(batch)](operator/regression/GbdtRegTrainBatchOp.md)
* [广义线性回归评估(batch)](operator/regression/GlmEvaluationBatchOp.md)
* [广义线性回归预测(batch)](operator/regression/GlmPredictBatchOp.md)
* [广义线性回归预测(stream)](operator/regression/GlmPredictStreamOp.md)
* [广义线性回归训练(batch)](operator/regression/GlmTrainBatchOp.md)
* [保序回归预测(batch)](operator/regression/IsotonicRegPredictBatchOp.md)
* [保序回归预测(stream)](operator/regression/IsotonicRegPredictStreamOp.md)
* [保序回归训练](operator/regression/IsotonicRegTrainBatchOp.md)
* [Lasso回归预测(batch)](operator/regression/LassoRegPredictBatchOp.md)
* [Lasso回归预测(stream)](operator/regression/LassoRegPredictStreamOp.md)
* [Lasso回归训练(batch)](operator/regression/LassoRegTrainBatchOp.md)
* [线性回归预测(batch)](operator/regression/LinearRegPredictBatchOp.md)
* [线性回归预测(stream)](operator/regression/LinearRegPredictStreamOp.md)
* [线性回归训练(batch)](operator/regression/LinearRegTrainBatchOp.md)
* [随机森林回归预测(batch)](operator/regression/RandomForestRegPredictBatchOp.md)
* [随机森林回归预测(stream)](operator/regression/RandomForestRegPredictStreamOp.md)
* [随机森林回归训练(batch)](operator/regression/RandomForestRegTrainBatchOp.md)
* [岭回归预测(batch)](operator/regression/RidgeRegPredictBatchOp.md)
* [岭回归预测(stream)](operator/regression/RidgeRegPredictStreamOp.md)
* [岭回归训练(batch)](operator/regression/RidgeRegTrainBatchOp.md)

### 聚类
* [二分K均值聚类预测(batch)](operator/clustering/BisectingKMeansPredictBatchOp.md)
* [二分K均值聚类预测(stream)](operator/clustering/BisectingKMeansPredictStreamOp.md)
* [二分K均值聚类训练(batch)](operator/clustering/BisectingKMeansTrainBatchOp.md)
* [经纬度K均值聚类预测batch](operator/clustering/GeoKMeansPredictBatchOp.md)
* [经纬度K均值聚类预测(stream)](operator/clustering/GeoKMeansPredictStreamOp.md)
* [经纬度K均值聚类训练(batch)](operator/clustering/GeoKMeansTrainBatchOp.md)
* [高斯混合模型预测(batch)](operator/clustering/GmmPredictBatchOp.md)
* [高斯混合模型预测(stream)](operator/clustering/GmmPredictStreamOp.md)
* [高斯混合模型训练(batch)](operator/clustering/GmmTrainBatchOp.md)
* [K均值聚类预测(batch)](operator/clustering/KMeansPredictBatchOp.md)
* [K均值聚类预测(stream)](operator/clustering/KMeansPredictStreamOp.md)
* [K均值聚类训练(batch)](operator/clustering/KMeansTrainBatchOp.md)
* [Lda预测(batch)](operator/clustering/LdaPredictBatchOp.md)
* [Lda预测(stream)](operator/clustering/LdaPredictStreamOp.md)
* [Lda训练](operator/clustering/LdaTrainBatchOp.md)
* [流式K均值聚类(stream)](operator/clustering/StreamingKMeansStreamOp.md)

### 关联规则
* [FpGrowth(batch)](operator/associationrule/FpGrowthBatchOp.md)
* [PrefixSpan(batch)](operator/associationrule/PrefixSpanBatchOp.md)

### 推荐
* [Als隐式训练](operator/recommendation/AlsImplicitTrainBatchOp.md)
* [Als：ItemsPerUser推荐(batch)](operator/recommendation/AlsItemsPerUserRecommBatchOp.md)
* [Als：ItemsPerUser推荐(stream)](operator/recommendation/AlsItemsPerUserRecommStreamOp.md)
* [Als：打分推荐推荐(batch)](operator/recommendation/AlsRateRecommBatchOp.md)
* [Als：打分推荐(stream)](operator/recommendation/AlsRateRecommStreamOp.md)
* [Als：相似items推荐(batch)](operator/recommendation/AlsSimilarItemsRecommBatchOp.md)
* [Als：相似items推荐(stream)](operator/recommendation/AlsSimilarItemsRecommStreamOp.md)
* [Als：相似users推荐(batch)](operator/recommendation/AlsSimilarUsersRecommBatchOp.md)
* [Als：相似users推荐(stream)](operator/recommendation/AlsSimilarUsersRecommStreamOp.md)
* [Als训练(batch)](operator/recommendation/AlsTrainBatchOp.md)
* [Als：UsersPerItem推荐(batch)](operator/recommendation/AlsUsersPerItemRecommBatchOp.md)
* [Als：UsersPerItem推荐(stream)](operator/recommendation/AlsUsersPerItemRecommStreamOp.md)
* [展开KObject(batch)](operator/recommendation/FlattenKObjectBatchOp.md)
* [展开KObject(stream)](operator/recommendation/FlattenKObjectStreamOp.md)
* [FM：ItemsPerUser推荐(batch)](operator/recommendation/FmItemsPerUserRecommBatchOp.md)
* [FM：ItemsPerUser推荐(stream)](operator/recommendation/FmItemsPerUserRecommStreamOp.md)
* [FM：打分推荐(batch)](operator/recommendation/FmRateRecommBatchOp.md)
* [FM二分类隐式训练(batch)](operator/recommendation/FmRecommBinaryImplicitTrainBatchOp.md)
* [FM推荐训练(batch)](operator/recommendation/FmRecommTrainBatchOp.md)
* [FM：UsersPerItem推荐(batch)](operator/recommendation/FmUsersPerItemRecommBatchOp.md)
* [FM：UsersPerItem推荐(stream)](operator/recommendation/FmUsersPerItemRecommStreamOp.md)
* [ItemCf：ItemsPerUser推荐(batch)](operator/recommendation/ItemCfItemsPerUserRecommBatchOp.md)
* [ItemCf：ItemsPerUser推荐(stream)](operator/recommendation/ItemCfItemsPerUserRecommStreamOp.md)
* [ItemCf：打分推荐(batch)](operator/recommendation/ItemCfRateRecommBatchOp.md)
* [ItemCf：打分推荐(stream)](operator/recommendation/ItemCfRateRecommStreamOp.md)
* [ItemCf：相似items推荐(batch)](operator/recommendation/ItemCfSimilarItemsRecommBatchOp.md)
* [ItemCf：相似items推荐(stream)](operator/recommendation/ItemCfSimilarItemsRecommStreamOp.md)
* [ItemCf训练(batch)](operator/recommendation/ItemCfTrainBatchOp.md)
* [ItemCf：UsersPerItem推荐(batch)](operator/recommendation/ItemCfUsersPerItemRecommBatchOp.md)
* [ItemCf：UsersPerItem推荐(stream)](operator/recommendation/ItemCfUsersPerItemRecommStreamOp.md)
* [推荐结果采样处理(batch)](operator/recommendation/LeaveKObjectOutBatchOp.md)
* [推荐结果TopK采样处理(batch)](operator/recommendation/LeaveTopKObjectOutBatchOp.md)
* [推荐负采样(batch)](operator/recommendation/NegativeItemSamplingBatchOp.md)
* [UserCf：ItemsPerUser推荐(batch)](operator/recommendation/UserCfItemsPerUserRecommBatchOp.md)
* [UserCf：ItemsPerUser推荐(stream)](operator/recommendation/UserCfItemsPerUserRecommStreamOp.md)
* [UserCf：打分推荐(batch)](operator/recommendation/UserCfRateRecommBatchOp.md)
* [UserCf：打分推荐(stream)](operator/recommendation/UserCfRateRecommStreamOp.md)
* [UserCf：相似users推荐(batch)](operator/recommendation/UserCfSimilarUsersRecommBatchOp.md)
* [UserCf：相似users推荐(stream)](operator/recommendation/UserCfSimilarUsersRecommStreamOp.md)
* [UserCf训练(batch)](operator/recommendation/UserCfTrainBatchOp.md)
* [UserCf：UsersPerItem推荐(batch)](operator/recommendation/UserCfUsersPerItemRecommBatchOp.md)
* [UserCf：UsersPerItem推荐(stream)](operator/recommendation/UserCfUsersPerItemRecommStreamOp.md)

### 评估
* [二分类评估(batch)](operator/evaluation/EvalBinaryClassBatchOp.md)
* [二分类评估(stream)](operator/evaluation/EvalBinaryClassStreamOp.md)
* [聚类评估(batch)](operator/evaluation/EvalClusterBatchOp.md)
* [多分类评估(batch)](operator/evaluation/EvalMultiClassBatchOp.md)
* [多分类评估(stream)](operator/evaluation/EvalMultiClassStreamOp.md)
* [多标签分类评估(batch)](operator/evaluation/EvalMultiLabelBatchOp.md)
* [排序评估(batch)](operator/evaluation/EvalRankingBatchOp.md)
* [回归评估(batch)](operator/evaluation/EvalRegressionBatchOp.md)

### 异常检测
* [Sos异常检测](operator/outlier/SosBatchOp.md)

### 在线学习
* [Ftrl模型过滤](operator/onlinelearning/FtrlModelFilterStreamOp.md)
* [Ftrl在线预测](operator/onlinelearning/FtrlPredictStreamOp.md)
* [Ftrl在线训练](operator/onlinelearning/FtrlTrainStreamOp.md)

### 相似度
* [字符串近似最近邻预测(batch)](operator/similarity/StringApproxNearestNeighborPredictBatchOp.md)
* [字符串近似最近邻训练](operator/similarity/StringApproxNearestNeighborTrainBatchOp.md)
* [字符串最近邻预测(batch)](operator/similarity/StringNearestNeighborPredictBatchOp.md)
* [字符串最近邻训练](operator/similarity/StringNearestNeighborTrainBatchOp.md)
* [字符串两两相似度计算(batch)](operator/similarity/StringSimilarityPairwiseBatchOp.md)
* [字符串两两相似度计算(stream)](operator/similarity/StringSimilarityPairwiseStreamOp.md)
* [文本近似最近邻预测(batch)](operator/similarity/TextApproxNearestNeighborPredictBatchOp.md)
* [文本近似最近邻训练](operator/similarity/TextApproxNearestNeighborTrainBatchOp.md)
* [文本最近邻预测(batch)](operator/similarity/TextNearestNeighborPredictBatchOp.md)
* [文本最近邻训练](operator/similarity/TextNearestNeighborTrainBatchOp.md)
* [文本两两相似度计算(batch)](operator/similarity/TextSimilarityPairwiseBatchOp.md)
* [文本两两相似度计算(stream)](operator/similarity/TextSimilarityPairwiseStreamOp.md)
* [向量近似最近邻预测(batch)](operator/similarity/VectorApproxNearestNeighborPredictBatchOp.md)
* [向量近似最近邻训练](operator/similarity/VectorApproxNearestNeighborTrainBatchOp.md)
* [向量最近邻预测(batch)](operator/similarity/VectorNearestNeighborPredictBatchOp.md)
* [向量最近邻训练](operator/similarity/VectorNearestNeighborTrainBatchOp.md)

### 工具类
* [Batch打印](operator/utils/PrintBatchOp.md)
* [Stream打印](operator/utils/PrintStreamOp.md)
* [UDF(batch)](operator/utils/UDFBatchOp.md)
* [UDF(stream)](operator/utils/UDFStreamOp.md)
* [UDTF(batch)](operator/utils/UDTFBatchOp.md)
* [UDTF(stream)](operator/utils/UDTFStreamOp.md)

## Pipeline 组件

### 数据处理
* [缺失值填充](pipeline/dataproc/Imputer.md)
* [缺失值填充模型](pipeline/dataproc/ImputerModel.md)
* [IndexToString](pipeline/dataproc/IndexToString.md)
* [KV转换](pipeline/dataproc/KeyToValue.md)
* [KeyToValues](pipeline/dataproc/KeyToValues.md)
* [绝对值最大化](pipeline/dataproc/MaxAbsScaler.md)
* [绝对值最大化模型](pipeline/dataproc/MaxAbsScalerModel.md)
* [归一化](pipeline/dataproc/MinMaxScaler.md)
* [归一化模型](pipeline/dataproc/MinMaxScalerModel.md)
* [MultiStringIndexer](pipeline/dataproc/MultiStringIndexer.md)
* [MultiStringIndexer模型](pipeline/dataproc/MultiStringIndexerModel.md)
* [标准化](pipeline/dataproc/StandardScaler.md)
* [标准化模型](pipeline/dataproc/StandardScalerModel.md)
* [StringIndexer](pipeline/dataproc/StringIndexer.md)
* [StringIndexer模型](pipeline/dataproc/StringIndexerModel.md)

#### 数据格式转换
* [列数据转csv](pipeline/dataproc/format/ColumnsToCsv.md)
* [列数据转json](pipeline/dataproc/format/ColumnsToJson.md)
* [列数据转kv](pipeline/dataproc/format/ColumnsToKv.md)
* [列数据转向量](pipeline/dataproc/format/ColumnsToVector.md)
* [csv转列数据](pipeline/dataproc/format/CsvToColumns.md)
* [csv转json](pipeline/dataproc/format/CsvToJson.md)
* [csv转kv](pipeline/dataproc/format/CsvToKv.md)
* [csv转向量](pipeline/dataproc/format/CsvToVector.md)
* [json转列数据](pipeline/dataproc/format/JsonToColumns.md)
* [json转csv](pipeline/dataproc/format/JsonToCsv.md)
* [json转kv](pipeline/dataproc/format/JsonToKv.md)
* [json转向量](pipeline/dataproc/format/JsonToVector.md)
* [kv转列数据](pipeline/dataproc/format/KvToColumns.md)
* [kv转csv](pipeline/dataproc/format/KvToCsv.md)
* [kv转json](pipeline/dataproc/format/KvToJson.md)
* [kv转向量](pipeline/dataproc/format/KvToVector.md)
* [向量转列数据](pipeline/dataproc/format/VectorToColumns.md)
* [向量转csv](pipeline/dataproc/format/VectorToCsv.md)
* [向量转json](pipeline/dataproc/format/VectorToJson.md)
* [向量转kv](pipeline/dataproc/format/VectorToKv.md)

#### 向量
* [向量聚合](pipeline/dataproc/vector/VectorAssembler.md)
* [向量元素依次相乘](pipeline/dataproc/vector/VectorElementwiseProduct.md)
* [向量缺失值填充](pipeline/dataproc/vector/VectorImputer.md)
* [向量缺失值填充模型](pipeline/dataproc/vector/VectorImputerModel.md)
* [向量元素两两相乘](pipeline/dataproc/vector/VectorInteraction.md)
* [向量绝对值最大化](pipeline/dataproc/vector/VectorMaxAbsScaler.md)
* [向量绝对值最大化模型](pipeline/dataproc/vector/VectorMaxAbsScalerModel.md)
* [向量归一化](pipeline/dataproc/vector/VectorMinMaxScaler.md)
* [向量归一化模型](pipeline/dataproc/vector/VectorMinMaxScalerModel.md)
* [向量标准化](pipeline/dataproc/vector/VectorNormalizer.md)
* [向量多项式展开](pipeline/dataproc/vector/VectorPolynomialExpand.md)
* [向量长度检验](pipeline/dataproc/vector/VectorSizeHint.md)
* [向量切片](pipeline/dataproc/vector/VectorSlicer.md)
* [向量标准化](pipeline/dataproc/vector/VectorStandardScaler.md)
* [向量标准化模型](pipeline/dataproc/vector/VectorStandardScalerModel.md)

### SQL
* [SQL操作：Select](pipeline/sql/Select.md)

### 特征工程
* [二值化](pipeline/feature/Binarizer.md)
* [分桶](pipeline/feature/Bucketizer.md)
* [离散余弦变换](pipeline/feature/DCT.md)
* [等宽离散化](pipeline/feature/EqualWidthDiscretizer.md)
* [等宽离散化模型](pipeline/feature/EqualWidthDiscretizerModel.md)
* [特征哈希](pipeline/feature/FeatureHasher.md)
* [独热编码](pipeline/feature/OneHotEncoder.md)
* [独热编码模型](pipeline/feature/OneHotEncoderModel.md)
* [主成分分析](pipeline/feature/PCA.md)
* [主成分分析模型](pipeline/feature/PCAModel.md)
* [分位数离散器](pipeline/feature/QuantileDiscretizer.md)
* [分位数离散器模型](pipeline/feature/QuantileDiscretizerModel.md)

### 文本
* [文本特征生成](pipeline/nlp/DocCountVectorizer.md)
* [文本特征生成模型](pipeline/nlp/DocCountVectorizerModel.md)
* [文本哈希特征生成](pipeline/nlp/DocHashCountVectorizer.md)
* [文本哈希特征生成模型](pipeline/nlp/DocHashCountVectorizerModel.md)
* [NGram](pipeline/nlp/NGram.md)
* [RegexTokenizer](pipeline/nlp/RegexTokenizer.md)
* [分词](pipeline/nlp/Segment.md)
* [停顿词过滤](pipeline/nlp/StopWordsRemover.md)
* [文本分解](pipeline/nlp/Tokenizer.md)
* [Word2Vec](pipeline/nlp/Word2Vec.md)
* [Word2Vec模型](pipeline/nlp/Word2VecModel.md)

### 分类
* [C45决策树分类](pipeline/classification/C45.md)
* [C45决策树分类模型](pipeline/classification/C45Model.md)
* [Cart](pipeline/classification/Cart.md)
* [Cart模型](pipeline/classification/CartModel.md)
* [决策树分类器模型](pipeline/classification/DecisionTreeClassificationModel.md)
* [决策树分类器](pipeline/classification/DecisionTreeClassifier.md)
* [FM分类](pipeline/classification/FmClassifier.md)
* [FM模型](pipeline/classification/FmModel.md)
* [GBDT分类器模型](pipeline/classification/GbdtClassificationModel.md)
* [GBDT分类器](pipeline/classification/GbdtClassifier.md)
* [Id3决策树分类](pipeline/classification/Id3.md)
* [Id3决策树分类模型](pipeline/classification/Id3Model.md)
* [最近邻分类模型](pipeline/classification/KnnClassificationModel.md)
* [最近邻分类](pipeline/classification/KnnClassifier.md)
* [线性支持向量机](pipeline/classification/LinearSvm.md)
* [线性支持向量机模型](pipeline/classification/LinearSvmModel.md)
* [逻辑回归](pipeline/classification/LogisticRegression.md)
* [逻辑回归模型](pipeline/classification/LogisticRegressionModel.md)
* [多层感知机模型](pipeline/classification/MultilayerPerceptronClassificationModel.md)
* [多层感知机分类](pipeline/classification/MultilayerPerceptronClassifier.md)
* [朴素贝叶斯](pipeline/classification/NaiveBayes.md)
* [朴素贝叶斯模型](pipeline/classification/NaiveBayesModel.md)
* [朴素贝叶斯文本分类器](pipeline/classification/NaiveBayesTextClassifier.md)
* [朴素贝叶斯文本分类模型](pipeline/classification/NaiveBayesTextModel.md)
* [OneVsRest](pipeline/classification/OneVsRest.md)
* [OneVsRest模型](pipeline/classification/OneVsRestModel.md)
* [随机森林模型](pipeline/classification/RandomForestClassificationModel.md)
* [随机森林分类器](pipeline/classification/RandomForestClassifier.md)
* [Softmax](pipeline/classification/Softmax.md)
* [Softmax模型](pipeline/classification/SoftmaxModel.md)

### 回归
* [生存回归](pipeline/regression/AftSurvivalRegression.md)
* [生存回归模型](pipeline/regression/AftSurvivalRegressionModel.md)
* [Cart回归](pipeline/regression/CartReg.md)
* [Cart回归模型](pipeline/regression/CartRegModel.md)
* [决策树回归模型](pipeline/regression/DecisionTreeRegressionModel.md)
* [决策树回归](pipeline/regression/DecisionTreeRegressor.md)
* [FM回归](pipeline/regression/FmRegressor.md)
* [GBDT回归模型](pipeline/regression/GbdtRegressionModel.md)
* [GBDT回归](pipeline/regression/GbdtRegressor.md)
* [广义线性回归](pipeline/regression/GeneralizedLinearRegression.md)
* [广义线性回归模型](pipeline/regression/GeneralizedLinearRegressionModel.md)
* [Isotonic回归](pipeline/regression/IsotonicRegression.md)
* [Isotonic回归模型](pipeline/regression/IsotonicRegressionModel.md)
* [Lasso回归](pipeline/regression/LassoRegression.md)
* [Lasso回归模型](pipeline/regression/LassoRegressionModel.md)
* [线性回归](pipeline/regression/LinearRegression.md)
* [线性回归模型](pipeline/regression/LinearRegressionModel.md)
* [随机森林回归模型](pipeline/regression/RandomForestRegressionModel.md)
* [随机森林回归](pipeline/regression/RandomForestRegressor.md)
* [岭回归](pipeline/regression/RidgeRegression.md)
* [岭回归模型](pipeline/regression/RidgeRegressionModel.md)

### 聚类
* [二分K均值聚类](pipeline/clustering/BisectingKMeans.md)
* [二分K均值聚类模型](pipeline/clustering/BisectingKMeansModel.md)
* [高斯混合模型](pipeline/clustering/GaussianMixture.md)
* [高斯混合模型](pipeline/clustering/GaussianMixtureModel.md)
* [经纬度K均值聚类](pipeline/clustering/GeoKMeans.md)
* [经纬度K均值聚类模型](pipeline/clustering/GeoKMeansModel.md)
* [K均值聚类](pipeline/clustering/KMeans.md)
* [K均值聚类模型](pipeline/clustering/KMeansModel.md)
* [Lda](pipeline/clustering/Lda.md)
* [Lda模型](pipeline/clustering/LdaModel.md)

### 推荐
* [Als：ItemsPerUser推荐](pipeline/recommendation/AlsItemsPerUserRecommender.md)
* [Als：打分推荐](pipeline/recommendation/AlsRateRecommender.md)
* [Als：相似items推荐](pipeline/recommendation/AlsSimilarItemsRecommender.md)
* [Als：相似users推荐](pipeline/recommendation/AlsSimilarUsersRecommender.md)
* [Als：UsersPerItem推荐](pipeline/recommendation/AlsUsersPerItemRecommender.md)
* [展开KObject](pipeline/recommendation/FlattenKObject.md)
* [FM：ItemsPerUser推荐](pipeline/recommendation/FmItemsPerUserRecommender.md)
* [FM：打分推荐](pipeline/recommendation/FmRateRecommender.md)
* [FM：UsersPerItem推荐](pipeline/recommendation/FmUsersPerItemRecommender.md)
* [ItemCf：ItemsPerUser推荐](pipeline/recommendation/ItemCfItemsPerUserRecommender.md)
* [ItemCf：打分推荐](pipeline/recommendation/ItemCfRateRecommender.md)
* [ItemCf：相似items推荐](pipeline/recommendation/ItemCfSimilarItemsRecommender.md)
* [ItemCf：UsersPerItem推荐](pipeline/recommendation/ItemCfUsersPerItemRecommender.md)
* [UserCf：ItemsPerUser推荐](pipeline/recommendation/UserCfItemsPerUserRecommender.md)
* [UserCf：打分推荐](pipeline/recommendation/UserCfRateRecommender.md)
* [UserCf：相似users推荐](pipeline/recommendation/UserCfSimilarUsersRecommender.md)
* [UserCf：UsersPerItem推荐](pipeline/recommendation/UserCfUsersPerItemRecommender.md)

### 模型选择和调参
* [网格搜索CV](pipeline/tuning/GridSearchCV.md)
* [网格搜索CV模型](pipeline/tuning/GridSearchCVModel.md)
* [网格搜索TV](pipeline/tuning/GridSearchTVSplit.md)
* [网格搜索TV模型](pipeline/tuning/GridSearchTVSplitModel.md)
* [随机搜索CV](pipeline/tuning/RandomSearchCV.md)
* [随机搜索CV模型](pipeline/tuning/RandomSearchCVModel.md)
* [随机搜索TV](pipeline/tuning/RandomSearchTVSplit.md)
* [随机搜索TV模型](pipeline/tuning/RandomSearchTVSplitModel.md)

### 相似度
* [字符串近似最近邻](pipeline/similarity/StringApproxNearestNeighbor.md)
* [字符串近似最近邻模型](pipeline/similarity/StringApproxNearestNeighborModel.md)
* [字符串最近邻](pipeline/similarity/StringNearestNeighbor.md)
* [字符串最近邻模型](pipeline/similarity/StringNearestNeighborModel.md)
* [文本近似最近邻](pipeline/similarity/TextApproxNearestNeighbor.md)
* [文本近似最近邻模型](pipeline/similarity/TextApproxNearestNeighborModel.md)
* [文本最近邻](pipeline/similarity/TextNearestNeighbor.md)
* [文本最近邻模型](pipeline/similarity/TextNearestNeighborModel.md)
* [向量近似最近邻](pipeline/similarity/VectorApproxNearestNeighbor.md)
* [向量近似最近邻模型](pipeline/similarity/VectorApproxNearestNeighborModel.md)
* [向量最近邻](pipeline/similarity/VectorNearestNeighbor.md)
* [向量最近邻模型](pipeline/similarity/VectorNearestNeighborModel.md)
