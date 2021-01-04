# Diabetic_Retinopathy_Using_BNN

Diabetic Retinopathy is one of the leading causes of blindness and eye disease in working age population of developed world. However the state-of-the-art techniques of deep learning models’ computation cost is expensive and consumes large amount of space. To apply these models to low computing devices is challenging task. To address this problem Binary Neural Networks (BNNs) could be best possible solution under research. BNNs have the ability to reduce the memory utilization and computational complexity of the neural network.

# EXISTING SYSTEM:

i)Conventional approach is when a DR occur, manual work had to be done to detect the retinopathy it is time-consuming and highly relies on the expertise of well-trained practitioners. There were no sophisticated tools for timely and error rate is high.

ii)Today, DNNs are almost exclusively trained on one or many very fast and power-hungry Graphic Processing Units (GPUs) . As a result, it is often a challenge to run DNNs on target low-power devices, and substantial research efforts are invested in speeding up DNNs at run-time on both general-purpose and specialized computer hardware. To solve this problem automated solution are presented but they are not feasible to use It also requires high computational power

# PROPOSED SYSTEM:


We introduce a method to train Binarized Neural Networks (BNNs) - neural networks with binary weights and activations at run-time. At training-time the binary weights and activations are used for computing the parameters gradients. During the forward pass, BNNs drastically reduce memory size and accesses, and replace most arithmetic operations with bit-wise operations, which is expected to substantially improve power-efficiency. To validate the effectiveness of BNNs we conduct experiments on the Kaggle DR dataset. BNNs achieved nearly state-of-the-art results over the kaggle DR dataset.


We show that during forward pass (runtime and train-time), BNNs drastically reduce memory consumption (size and number of accesses), and replace most arithmetic operations with bit-wise operations, which potentially lead to a substantial increase in power-efficiency. Moreover, a binarized CNN can lead to binary convolution kernel repetitions; We argue that dedicated hardware could reduce the time complexity by 60% .
