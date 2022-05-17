# Hidden-Quantum-Markov-model-and-its-extensions
量子隐马尔科夫模型和分离量子隐马尔可夫模型的代码实现
需要的python pacakge和文件说明：
  1. numpy (用于基本的数值计算)
  2. autograd (求解似然函数梯度)
  3. qiskit (用量子线路生成任意维度的密度矩阵)
  4. matplotlib 绘制图像
  5. os、sys用于操作系统进行文件的存储：
  6. HQMM_Backup.py 定义了基本的类来描述量子隐马尔可夫模型和马尔科夫模型
  7. model.py构建的模型和实例化
  8. 数据 train_sequence.txt, val_sequence.txt, test_sequence.txt是来自量子试验斯特恩-盖拉赫实验的试验数据
  9. 数据seq_hmm_train.txt、seq_hmm_val.txt、seq_hmm_test.txt是来自一个隐马尔可夫模型的数据，可以利用转移矩阵和观测矩阵进行生成
