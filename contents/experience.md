### **1. Knowledge Graph-Based Intelligent Text Generation Project**  

Developed a military knowledge graph that simulates real-world environments to analyze multi-source intelligence, link graph data, and provide multi-target, multi-scenario information analysis and feedback.

#### Key Contributions:  
- Knowledge-graph construction: ingested and parsed multi-source structured and semi-structured data; built a weapons-and-equipment knowledge graph containing 20,000 nodes.
- Information Extraction: Applied the CasRel relation extraction model to perform sentence-level information extraction, achieving 90.0% accuracy and 93.3% recall.
- Text Generation: Generated structured intelligence reports based on entity-linking results using a slot-grammar method, achieving a ROUGE-2 score of 73.1%.

### **1. 基于知识图谱的文本智能生成项目**  

构建军事知识图谱，模拟真实环境解析多源情报数据，链接图谱并实现多目标多场景下的信息解析与反馈

#### 主要贡献:  
- 图谱构建：获取解析多源结构化、半结构化数据，构建武器装备类知识图谱节点数为20000个  
- 信息抽取：基于CasRel关系抽取模型解决句子级文本信息抽取，acc为90.0%，recall为93.3%  
- 文本生成：基于实体链接结果与槽语法方法生成特定格式的情报，文本生成Rouge2值为73.1%

---

### **2. Geospatial Knowledge Graph and Knowledge-Base Engine Project**  

Construction of a geospatial knowledge graph and development of a geospatial knowledge-base reasoning engine.

#### Key Contributions:  
- Human–machine collaborative knowledge-graph construction: built multimodal knowledge graphs guided by expert knowledge through knowledge alignment, knowledge completion, and conflict resolution.
- Sustainable Knowledge-Graph Updating: fused multimodal knowledge graphs to establish knowledge-graph provenance protection, and applied distributed fusion methods to continuously update the graph.  
- Knowledge Base Reasoning Engine: Supported conflict detection and algorithmic chain reasoning through rule-based, link-based, and ontology-based inference.  

### **2. 地理空间知识图谱与知识库引擎项目**  

地理空间知识图谱构建，以及地理空间知识库推理引擎研发

#### 主要贡献:  
- 知识图谱人机协同共建：以专家知识为导向，通过知识对齐、知识补全、冲突消解，实现多模态知识图谱构建  
- 知识图谱可持续更新：多模态知识图谱融合，形成知识图谱产权保护，采用分布式融合更新图谱  
- 知识库推理引擎：通过规则推理、链路推理和本体推理，支撑冲突检测、算法链路推理等

---

### **3. Urban Public Health Simulation and Modeling Technology Research**  

For urban public health epidemic events, extracted event information, mined causal relationships between events, constructed a cause-and-effect knowledge graph, and captured spatiotemporal co-occurrence information from case trajectories.

#### Key Contributions:  
- Event Extraction: Extracted event elements using a BERT-BiGRU-CRF trigger word recognition model, achieving 79% accuracy.
- Cause-and-Effect Knowledge Graph Construction: Centered on epidemic news reports, constructed a cause-and-effect knowledge graph with 9,000 nodes through event generalization and causal logic between events.  

### **3. 城市公共卫生模拟仿真技术研究**  

针对城市公共卫生疫情事件，抽取事件信息挖掘事件之间因果联系，构建事理知识图谱，获取病例轨迹间的时空伴随信息

#### 主要贡献:  
- 事件抽取：通过BERT-BiGRU-CRF事件触发词识别模型，抽取事件要素，acc为79%  
- 事理图谱构建：以疫情新闻报道为核心，通过事件泛化和事件间因果逻辑，构建事理图谱节点数为9000个

---

### **4. Research on Target Detection and Tracking Technology**  

For maritime and aerial targets, extracted open-source intelligence data, analyzed target behavior patterns, and predicted target trajectories based on AIS and ADS-B data.

#### Key Contributions:  
- Knowledge Extraction: Leveraged the Qwen2.5-VL-3B large model with domain-adaptive fine-tuning to extract target text intelligence knowledge and integrate features from multimodal data.
- Trajectory Prediction: Predicted maritime target trajectories using a Seq2Seq Attention model and aerial target trajectories using a trajectory clustering algorithm based on a hybrid temporal model.

### **4. 目标识别跟踪技术研究**  

针对海上和空中目标，抽取目标开源本文情报数据，挖掘目标行为规律，基于AIS与ADS-B数据进行目标轨迹预测

#### 主要贡献:  
- 知识抽取：基于Qwen2.5-VL-3B大模型，通过领域适应微调，抽取目标文本情报知识，并提取融合多模态数据特征
- 轨迹预测：基于Seq-Seq Attention模型，实现海上目标轨迹预测；基于混合时序模型的轨迹聚类算法，实现空中目标轨迹预测