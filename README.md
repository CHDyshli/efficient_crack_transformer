# Efficient Crack Transformer
Efficient Dual-Branch High-Resolution Transformer Design for Crack Segmentation

# Abstract
Recent studies show that Transformer-based crack segmentation models deliver impressive results. However, due to the quadratic complexity of the self-attention mechanism, the computational cost becomes prohibitive when handling high-resolution dense prediction tasks. This paper presents an efficient Transformer-based network for crack segmentation, utilizing several specially optimized self-attention modules. The proposed model incorporates a dual-branch structure, consisting of a high-resolution branch that maintains high resolution throughout and a low-resolution branch that progressively reduces resolution. A multi-scale spatial-reduction attention is introduced to the high-resolution branch to capture fine details, while an enhanced ReLU-based linear attention in the low-resolution branch learns global features. A bidirectional cross-resolution feature enhancement module connects the two branches, facilitating comprehensive information fusion. On the combined dataset CrackSeg9k and the scenario-specific datasets Asphalt3k and Concrete3k , the proposed method obtains mIoU of \textbf{81.85\%,81.29\%, and 86.36\%,} respectively, which outperforms the comparative state-of-the-art models and also achieves the best trade-off between efficiency and performance.

# Dataset
* CrackSeg9k originates from [CrackSeg9k: a collection and benchmark for crack segmentation datasets and frameworks](https://github.com/Dhananjay42/crackseg9k).
* Asphalt3k and Concrete3k are from [Real-time High-Resolution Neural Network with Semantic Guidance for Crack Segmentation](https://github.com/CHDyshli/HrSegNet4CrackSegmentation).



## The code will be released soon.


