# ML_Data

# CyberPhysical Attack
IoT incorporates the digital and physical attributes to optimize the regular tasks involved in Cyber-Physical Systems (CPS), smart grids, smart cities and IIoT [1]. The IIoT was introduced to improve the communication between industrial and consumer-based applications. ICS is among the Critical Infrastructures (CIs) that highly rely on IoT networks and aim to increase the profitability and production of Industry 4.0. The complexity of ICS is evident in the distribution of industrial services and the adoption of industrialized techniques, including in manufacturing industries, water treatment plants, gas pipelines, and power plants[2]. The role of cybersecurity is more significant as the contribution of IIoT makes a greater impact on the growth of business operations. 
  However, the escalating number of devices involved in IIoT networks raises concerns about safeguarding ICS, becoming a serious threat to business operations [3] and creating complex attack surfaces for control and network elements in CPS networks. The existing security mechanisms like authentication systems, firewalls, and IDS are inefficient against advanced cyber attacks like Flame [4], Duqu [5], and seismic attacks [6] that exploit ICS networks due to the varying protocols [7].In the emerging digital era, the researchers focused on developing the IDS that is capable of protecting the intricate attack scenarios [8]. Most of the existing approaches rely on static rules and predefined behaviours which are limited to recognising only the known attack scenario. In addition, most of the IDSs are tailored for generic communication protocols like TCP and UDP, neglecting control protocols like Modbus and DNP3 [8]. These limitations make the IDS weaker and exhibit a low detection rate due to extensive security features, overfitting, and imbalanced data. The above-mentioned scenarios insist the research medium provide a robust attack detection approach to protect IIoT-based networks against cyber-attacks, ensuring reliability. Extracting the relevant features from the CPS network and control data remains a significant challenge to enhance detection accuracy and reduce false alarms [9].


   #  CONVOLUTIONAL NEURALNETWORK
 The CNN is a type of feed-forward neural network designed to extract hierarchical and spatial information from data. In the context of the UNSW-NB15 dataset, CNN is employed to analyze and classify the different attacks. During training, the model learns from input data by defining a set of filter values that enable it to recognize patterns and features within the input data. These filters systematically scan the input data, extracting relevant information at different layers of the network. As the input data passes through the layers, the network adjusts its weights through backpropagation, minimizing errors and refining itsability to classify network traffic accurately. By using convolutional filters to map parts of the input data with varying window sizes and strides, CNN efficiently captures features within the input data. This hierarchical feature extraction process makes CNN well-suited for tasks such as classifying network traffic into different categories based on its characteristics.

 # LONG SHORT-TERMMEMORY
 The LSTM network is a type of Recurrent Neural network (RNN) designed to process and classify sequential data, such as time series or natural language text. In the context of the UNSW NB15 dataset, LSTM networks are utilized to analyze and classify various attacks.During training, the LSTM model learns from input sequences by dynamically updating its memory cells, which enables it to capture long-term dependencies and temporal patterns within the data. Unlike traditional RNNs, LSTM networks incorporate gated mechanisms that regulate the flow of information through the network, allowing them to retain information over extended time periods and mitigate the vanishing gradient problem. The LSTM networkoperates by processing input sequences step by step, with each step updating its internal state based on the current input and the previous state. This process enables the network to learn intricate patterns and relationships within the sequential data. Through backpropagation, the network adjusts its parameters, including the weights and biases of the gates, to minimizeerrors and optimize its ability to classify network traffic accurately.

  # HYBRID CNN+LSTM MODEL
 A hybrid CNN-LSTM model combines the strengths of Convolutional Neural Networks and Long Short-Term Memory networks to analyze and classify sequential data such as network traffic, as seen in the context of the UNSW-NB15 dataset. This model architecture integrates the hierarchical feature extraction capabilities of CNNs with the ability of LSTMs to capture long-term dependencies and temporal patterns within sequential data. During training, the hybrid model leverages CNN layers to extract spatial features from theinput data, such as patterns and structures within the network traffic. These CNN layers consist of convolutional filters that systematically scan the input data, capturing relevant information at different levels of abstraction. The output of the CNN layers is then passed to the LSTM layers, which process the sequential data over time steps. Within the LSTM layers, the model dynamically updates its memory cells based on the sequential input, allowing it to capture both short-term and long-term dependencies within the data. The gated mechanisms within the LSTM architecture regulate the flow of information, enabling the model to retain important contextual information over extended periods. Through the joint training of both CNN-based and LSTM-based components, the hybrid model learns to effectively classify network traffic into different categories based on its characteristics. As the input data passes through the layers, the model adjusts its parameters through backpropagation, optimizing its ability to accurately classify various types of network attacks.
