# BiLSTM_basedFederatedLearning
基于Bilastm联邦学习机制的任务预测的MEC环境下的计算卸载算法

      Mobile edge computing (MEC) driven by 5G cellular systems has recently become a promising and efficient paradigm for enhancing the data processing capabilities of low-power networks, such as wireless sensor networks and the internet of things. In this article, we first propose a novel thoughtful intelligent task prediction mechanism based on Bi-directional long short-term memory (BiLSTM), which is implemented under cloud-edge-end three-layer federated learning (FL) framework. Each participating terminal device independently trains the model locally without uploading data to server. Subsequently, model aggregation is performed regularly at the edge and the cloud. The purpose of the construction is to jointly train a general global BiLSTM model to predict the data volume information of computing tasks, etc., so as to more accurately guide computing offloading decisions and resource allocation. This mechanism eliminates the need to solve complex optimization problems and greatly reduces computational complexity, especially in large networks.
	
      In order to further reduce the network communication overhead of FL in the model optimization process, we improved the federated learning and a federated averaging (FAVG) algorithm, and only the important gradients selected were uploaded to the parameter server after the parameter sparse method. Finally, the experimental results show that our algorithm is better than other learning-based offloading algorithms in prediction accuracy without collecting user private data.
