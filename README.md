# Awesome Federated Machine Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
Federated Learning (FL) is a new machine learning framework, which enables multiple devices collaboratively to train a shared model without compromising data privacy and security.  

<div align=center>
<img width="700" src="images/cover.png" alt="FL"/>
</div>

This repository will continue to be collected and updated everything about federated learning materials, including research papers, conferences, blogs and beyond.



## Table of Contents

 - [Top Machine Learning Conferences](#top-machine-learning-conferences)
     + [ICML](#ICML)&emsp;[ICLR](#ICLR)&emsp;[NeurIPS](#NeurIPS)   
 - [Top Computer Vision Conferences](#top-computer-vision-conferences)
     + [CVPR](#CVPR)&emsp;[ICCV](#ICCV)&emsp;[ECCV](#ECCV)   
 - [Top Artificial Intelligence and Data Mining Conferences](#top-artificial-intelligence-and-data-mining-conferences)
     + [AAAI](#AAAI)&emsp;[AISTATS](#AISTATS)&emsp;[KDD](#KDD) 	 
 - [Books](#Books)
 - [Papers (Research directions)](#papers)
     + [Model Aggregation](#1-Model-Aggregation)
	 + [Personalization](#2-Personalization)&emsp;&emsp; 
	 + [Recommender system](#3-Recommender-system)
	 + [Security](#4-Security)&emsp;&emsp;
	 + [Survey](#5-Survey)&emsp;&emsp;
	 + [System Architecture](#6-System-Design)
	 + [Efficiency](#7-Communication-Efficient)&emsp;&emsp;
	 + [Optimization](#8-Optimization)&emsp;&emsp; 
	 + [Fairness](#9-Fairness)<br>
	 + [Application](#10-Applications)&emsp;&emsp;
	 + [Boosting](#11-Boosting)&emsp;&emsp;
	 + [Incentive mechanism](#12-Incentive-mechanism)
	 + [Unsupervised Learning](#13-Unsupervised-Learning)&emsp;&emsp;
	 + [Heterogeneity](#14-Heterogeneity)&emsp;&emsp;
	 + [Client Selection](#15-Client-Selection)
	 + [Graph Neural Networks](#16-Graph-Neural-Networks)
 - [Google FL Workshops](#google-fl-workshops)	 
 - [Videos and Lectures](#Videos-and-Lectures)
 - [Tutorials and Blogs](#Tutorials-and-Blogs)
 - [Open-Sources](#open-sources)

&nbsp; 

## Top Machine Learning Conferences

In this section, we will summarize Federated Learning papers accepted by top machine learning conference, Including NeurIPS, ICML, ICLR.

### ICML 
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.15pt'>
        <td rowspan=18 height=342 class=xl6519452 style='height:242.25pt' align="center"><a href="https://icml.cc/Conferences/2021/Schedule?type=Poster">ICML 2021</a></td>
        <td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/2106.06089.pdf">Gradient Disaggregation: Breaking Privacy in Federated Learning by Reconstructing the User Participant Matrix</a></td>
        <td class=xl6519452 align="center"><font size="2">Harvard University</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38958558/gradient-disaggregation-breaking-privacy-in-federated-learning-by-reconstructing-the-user-participant-matrix">video</a><br><a href="https://github.com/gdisag/gradient_disaggregation">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.05001.pdf">FL-NTK: A Neural Tangent Kernel-based Framework for Federated Learning Analysis</a></td>
        <td class=xl6519452 align="center"><font size="2">Peking University;<br> Princeton University</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959650/flntk-a-neural-tangent-kernelbased-framework-for-federated-learning-analysis">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.04628.pdf">Personalized Federated Learning using Hypernetworks</a></td>
        <td class=xl6519452 align="center"><font size="2">Bar-Ilan University;<br> NVIDIA </font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/AvivSham/pFedHN">code</a><br><a href="https://avivsham.github.io/pfedhn/">HomePage</a><br><a href="https://slideslive.com/38959583/personalized-federated-learning-using-hypernetworks">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2011.08474.pdf">Federated Composite Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">Stanford University;<br> Google</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/hongliny/FCO-ICML21">code</a><br><a href="https://www.youtube.com/watch?v=tKDbc60XJks&ab_channel=FederatedLearningOneWorldSeminar">video</a><br><a href="https://hongliny.github.io/files/FCO_ICML21/FCO_ICML21_slides.pdf">slides</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.07078.pdf">Exploiting Shared Representations for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Texas at Austin;<br> University of Pennsylvania</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/lgcollins/FedRep">code</a><br><a href="https://slideslive.com/38959519/exploiting-shared-representations-for-personalized-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.10056.pdf">Data-Free Knowledge Distillation for Heterogeneous Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Michigan State University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/zhuangdizhu/FedGen">code</a><br><a href="https://slideslive.com/38959429/datafree-knowledge-distillation-for-heterogeneous-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.03196.pdf">Federated Continual Learning with Weighted Inter-client Transfer</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/wyjeong/FedWeIT">code</a><br><a href="https://slideslive.com/38959323/federated-continual-learning-with-weighted-interclient-transfer">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.04635.pdf">Federated Deep AUC Maximization for Hetergeneous Data with a Constant Communication Complexity</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Iowa</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959235/federated-deep-auc-maximization-for-hetergeneous-data-with-a-constant-communication-complexity">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.03198.pdf">Bias-Variance Reduced Local SGD for Less Heterogeneous Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Tokyo</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959169/biasvariance-reduced-local-sgd-for-less-heterogeneous-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2104.08776.pdf">Federated Learning of User Verification Models Without Sharing Embeddings</a></td>
        <td class=xl6519452 align="center"><font size="2">Qualcomm</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38958858/federated-learning-of-user-verification-models-without-sharing-embeddings">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.05883.pdf">Clustered Sampling: Low-Variance and Improved Representativity for Clients Selection in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Accenture</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/Accenture//Labs-Federated-Learning/tree/clustered_sampling">code</a><br><a href="https://slideslive.com/38959618/clustered-sampling-lowvariance-and-improved-representativity-for-clients-selection-in-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.04221.pdf">Ditto: Fair and Robust Federated Learning Through Personalization</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU;<br> Facebook AI</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/litian96/ditto">code</a><br><a href="https://slideslive.com/38955195/ditto-fair-and-robust-federated-learning-through-personalization">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.00697.pdf">Heterogeneity for the Win: One-Shot Federated Clustering</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959380/heterogeneity-for-the-win-oneshot-federated-clustering">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.06387.pdf">The Distributed Discrete Gaussian Mechanism for Federated Learning with Secure Aggregation</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959306/the-distributed-discrete-gaussian-mechanism-for-federated-learning-with-secure-aggregation">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v139/acar21a/acar21a.pdf">Debiasing Model Updates for Improving Personalized Federated Training</a></td>
        <td class=xl6519452 align="center"><font size="2">Boston University;<br> Arm </font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959212/debiasing-model-updates-for-improving-personalized-federated-training">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.03228.pdf">One for One, or All for All: Equilibria and Optimality of Collaboration in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Toyota;<br>Berkeley;<br> Cornell University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/rlphilli/Collaborative-Incentives">code</a><br><a href="https://slideslive.com/38959135/one-for-one-or-all-for-all-equilibria-and-optimality-of-collaboration-in-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.08283.pdf">CRFL: Certifiably Robust Federated Learning against Backdoor Attacks</a></td>
        <td class=xl6519452 align="center"><font size="2">UIUC;<br>IBM</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/AI-secure/CRFL">code</a><br><a href="https://slideslive.com/38959047/crfl-certifiably-robust-federated-learning-against-backdoor-attacks">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://assets.amazon.science/11/23/3e0cfaf1456d80ecf3f37a2cd812/federated-learning-under-arbitrary-communication-patterns.pdf">Federated Learning under Arbitrary Communication Patterns</a></td>
        <td class=xl6519452 align="center"><font size="2">Indiana University;<br> Amazon</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959048/federated-learning-under-arbitrary-communication-patterns">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td rowspan=6 height=114 class=xl6519452 style='height:85.5pt' align="center"><a href="https://icml.cc/Conferences/2020/Schedule?type=Poster">ICML 2020</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v119/hamer20a/hamer20a.pdf">FedBoost: A Communication-Efficient Algorithm for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928463/fedboost-a-communicationefficient-algorithm-for-federated-learning?ref=speaker-16993-latest">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.07682.pdf">FetchSGD: Communication-Efficient Federated Learning with Sketching</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley;<br>Johns Hopkins University;<br>Amazon</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928454/fetchsgd-communicationefficient-federated-learning-with-sketching">Video</a><br><a href="https://github.com/kiddyboots216/CommEfficient">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1910.06378.pdf">SCAFFOLD: Stochastic Controlled Averaging for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL;<br>Google</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38927610/scaffold-stochastic-controlled-averaging-for-federated-learning">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2004.10342">Federated Learning with
		Only Positive Labels</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928322/federated-learning-with-only-positive-labels">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2004.01442.pdf">From Local SGD to Local Fixed-Point Methods for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Moscow Institute of Physics and Technology;<br>KAUST</font></td>
        <td class=xl6519452 align="center"><a href="https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-18-00UTC-6590-from_local_sgd.pdf">Slide</a><br><a href="https://slideslive.com/38928320/from-local-sgd-to-local-fixed-point-methods-for-federated-learning">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/2002.11364">Acceleration for Compressed Gradient Descent in Distributed and Federated Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">KAUST</font></td>
        <td class=xl6519452 align="center"><a href="https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-19-00UTC-6191-acceleration_fo.pdf">Slide</a><br><a href="https://slideslive.com/38927921/acceleration-for-compressed-gradient-descent-in-distributed-optimization">Video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center"><a href="https://icml.cc/Conferences/2019/Schedule?type=Poster">ICML 2019</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1905.12022.pdf">Bayesian Nonparametric Federated Learning of Neural Networks</a></td>
        <td class=xl6519452 align="center"><font size="2">IBM</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/IBM/probabilistic-federated-neural-matching">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/1811.12470">Analyzing Federated Learning through an Adversarial Lens</a></td>
        <td class=xl6519452 align="center"><font size="2">Princeton University;<br>IBM</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/inspire-group/ModelPoisoning">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/pdf/1902.00146.pdf">Agnostic Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google </font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
</table>


### ICLR

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=21 height=399 class=xl6519452 style='height:242.25pt' align="center">ICLR 2022</td>
		<td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/2111.04706.pdf">Bayesian Framework for Gradient Leakage</a></td>
        <td class=xl6519452 align="center"><font size="2">ETH Zurich</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=WHA8009laxu">Unsupervised Federated Learning is Possible</a></td>
        <td class=xl6519452 align="center"><font size="2"></font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2108.06869.pdf">Reducing the Communication Cost of Federated Learning through Multistage Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">Carnegie Mellon University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=541PxiEKN3F">Acceleration of Federated Learning with Alleviated Forgetting in Local Training</a></td>
        <td class=xl6519452 align="center"><font size="2">Tsinghua University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2108.06098.pdf">FedPara: Low-rank Hadamard Product for Communication-Efficient Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">POSTECH</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=Xo0lbDt975">An Agnostic Approach to Federated Learning with Class Imbalance</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Pennsylvania </font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=_QLmakITKg">Efficient Split-Mix Federated Learning for On-Demand and In-Situ Customization</a></td>
        <td class=xl6519452 align="center"><font size="2">Michigan State University;<br>The University of Texas at Austin</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/illidanlab/SplitMix">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2110.13057.pdf">Robbing the Fed: Directly Obtaining Private Data in Federated Learning with Modified Models</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Maryland</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=2sDQwC_hmnM">ZeroFL: Efficient On-Device Training for Federated Learning with Local Sparsity</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Cambridge</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=nwKXyFvaUm">Diverse Client Selection for Federated Learning via Submodular Maximization</a></td>
        <td class=xl6519452 align="center"><font size="2">Intel;<br>Carnegie Mellon University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2202.00280.pdf">Recycling Model Updates in Federated Learning: Are Gradient Subspaces Low-Rank? </a></td>
        <td class=xl6519452 align="center"><font size="2">Purdue University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/shams-sam/FedOptim">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=E4EE_ohFGz">Diurnal or Nocturnal? Federated Learning of Multi-branch Networks from Periodically Shifting Distributions </a></td>
        <td class=xl6519452 align="center"><font size="2">University of Maryland;<br>Google</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2110.15210.pdf">Towards Model Agnostic Federated Learning Using Knowledge Distillation</a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=oVE1z8NlNe">Divergence-aware Federated Self-Supervised Learning</a></td>
        <td class=xl6519452 align="center"><font size="2"> Nanyang Technological University;<br>SenseTime</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2110.14216.pdf">What Do We Mean by Generalization in Federated Learning? </a></td>
        <td class=xl6519452 align="center"><font size="2">Stanford University;<br>Google</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.06042.pdf">FedBABU: Toward Enhanced Representation for Federated Image Classification </a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/jhoon-oh/FedBABU">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2006.09365.pdf">Byzantine-Robust Learning on Heterogeneous Datasets via Bucketing </a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/liehe/byzantine-robust-noniid-optimizer">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2201.12467.pdf">Improving Federated Learning Face Recognition via Privacy-Agnostic Clusters</a></td>
        <td class=xl6519452 align="center"><font size="2">Aibee</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/IrvingMeng/MagFace">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=H0oaWl6THa">Hybrid Local SGD for Federated Learning with Heterogeneous Communications </a></td>
        <td class=xl6519452 align="center"><font size="2">University of Texas;<br>	Pennsylvania State University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2107.00778.pdf">On Bridging Generic and Personalized Federated Learning for Image Classification </a></td>
        <td class=xl6519452 align="center"><font size="2">The Ohio State University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2110.10342.pdf">Minibatch vs Local SGD with Shuffling: Tight Convergence Bounds and Beyond</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=10 height=190 class=xl6519452 style='height:242.25pt' align="center">ICLR 2021</td>
		<td class=xl6519452 align="center"><a href="https://openreview.net/pdf?id=B7v4QMR6Z9w">Federated Learning Based on Dynamic Regularization</a></td>
        <td class=xl6519452 align="center"><font size="2">Boston University;<br>ARM</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=jDdzh5ul-d">Achieving Linear Speedup with Partial Worker Participation in Non-IID Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">The Ohio State University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.01264.pdf">HeteroFL: Computation and Communication Efficient Federated Learning for Heterogeneous Clients</a></td>
        <td class=xl6519452 align="center"><font size="2">Duke University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/dem123456789/HeteroFL-Computation-and-Communication-Efficient-Federated-Learning-for-Heterogeneous-Clients">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=Ogga20D2HO-">FedMix: Approximation of Mixup under Mean Augmented Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.05273.pdf">Federated Learning via Posterior Averaging: A New Perspective and Practical Algorithms</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU; Google</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/alshedivat/fedpa">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.00295.pdf">Adaptive Federated Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/google-research/federated/tree/master/optimization">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=ehJqJQk9cw">Personalized Federated Learning with First Order Model Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">Stanford University; NVIDIA</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=6YEQUn0QICG">FedBN: Federated Learning on Non-IID Features via Local Batch Normalization</a></td>
        <td class=xl6519452 align="center"><font size="2">Princeton University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/med-air/FedBN">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2009.01974.pdf">FedBE: Making Bayesian Model Ensemble Applicable to Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">The Ohio State University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=ce6CFXBh30h">Federated Semi-Supervised Learning with Inter-Client Consistency & Disjoint Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/wyjeong/FedMatch">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=7 height=133 class=xl6519452 style='height:85.5pt' align="center">ICLR 2020</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://openreview.net/pdf?id=HJezF3VYPB">Federated Adversarial Domain Adaptation</a></td>
        <td class=xl6519452 align="center"><font size="2">Boston University;<br>Columbia University;<br>Rutgers University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=rkgyS0VFvr">DBA: Distributed Backdoor Attacks against Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Zhejiang University;<br>IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/AI-secure/DBA">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=ByexElSYDr">Fair Resource Allocation in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU;<br>Facebook AI</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/litian96/fair_flearn">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=BkluqlSFDS">Federated Learning with Matched Averaging</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Wisconsin-Madison;<br>IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/IBM/FedMA">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=rJgqMRVYvr">Differentially Private Meta-Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://openreview.net/pdf?id=SJgaRA4FPH">Generative Models for Effective ML on Private, Decentralized Datasets</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/tensorflow/gan">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://openreview.net/pdf?id=HJxNAnVtDS">On the Convergence of FedAvg on Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">Peking University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/lx10077/fedavgpy">Code</a></td>
	</tr>
</table>

### NeurIPS
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
        <td rowspan=33 height=627 class=xl6519452 style='height:242.25pt' align="center"><a href="https://papers.nips.cc/paper/2021">NeurIPS 2021</a></td>
		<td class=xl6519452 align="center"><a href="https://proceedings.neurips.cc/paper/2021/file/076a8133735eb5d7552dc195b125a454-Paper.pdf">Sageflow: Robust Federated Learning against Both Stragglers and Adversaries</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/076a8133735eb5d7552dc195b125a454-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/08040837089cdf46631a10aca5258e16-Paper.pdf">CAFE: Catastrophic Data Leakage in Vertical Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Rensselaer Polytechnic Institute;<br>IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/DeRafael/CAFE">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/08040837089cdf46631a10aca5258e16-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/080acdcce72c06873a773c4311c2e464-Paper.pdf">Fault-Tolerant Federated Reinforcement Learning with Theoretical Guarantee</a></td>
        <td class=xl6519452 align="center"><font size="2">NUS</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/flint-xf-fan/Byzantine-Federeated-RL">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/080acdcce72c06873a773c4311c2e464-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/09a5e2a11bea20817477e0b1dfe2cc21-Paper.pdf">Optimality and Stability in Federated Learning: A Game-theoretic Approach</a></td>
        <td class=xl6519452 align="center"><font size="2">Cornell University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/kpdonahue/model_sharing_games">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/09a5e2a11bea20817477e0b1dfe2cc21-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/1dba3025b159cd9354da65e2d0436a31-Paper.pdf">QuPeD: Quantized Personalization via Distillation with Applications to Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">UCLA</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/1dba3025b159cd9354da65e2d0436a31-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/285baacbdf8fda1de94b19282acd23e2-Paper.pdf">The Skellam Mechanism for Differentially Private Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google Research;<br>CMU</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/285baacbdf8fda1de94b19282acd23e2-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/2f2b265625d76a6704b08093c652fd79-Paper.pdf">No Fear of Heterogeneity: Classifier Calibration for Federated Learning with Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">NUS; <br> Huawei</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/2f2b265625d76a6704b08093c652fd79-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/3016a447172f3045b65f5fc83e04b554-Paper.pdf">STEM: A Stochastic Two-Sided Momentum Algorithm Achieving Near-Optimal Sample and Communication Complexities for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Minnesota</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/3016a447172f3045b65f5fc83e04b554-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/34adeb8e3242824038aa65460a47c29e-Paper.pdf">Subgraph Federated Learning with Missing Neighbor Generation</a></td>
        <td class=xl6519452 align="center"><font size="2">Emory University; <br> University of British Columbia; <br> Lehigh University</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/34adeb8e3242824038aa65460a47c29e-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/3b3fff6463464959dcd1b68d0320f781-Paper.pdf">Evaluating Gradient Inversion Attacks and Defenses in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Princeton University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/JonasGeiping/invertinggradients">Code</a><br><a href="https://papers.neurips.cc/paper/2021/hash/3b3fff6463464959dcd1b68d0320f781-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.15482.pdf">Personalized Federated Learning With Gaussian Processes</a></td>
        <td class=xl6519452 align="center"><font size="2">Bar-Ilan University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/IdanAchituve/pFedGP">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/46d0671dd4117ea366031f87f3aa0093-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/4c27cea8526af8cfee3be5e183ac9605-Paper.pdf">Differentially Private Federated Bayesian Optimization with Distributed Exploration</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT;<br>NUS</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/daizhongxiang/Differentially-Private-Federated-Bayesian-Optimization">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/4c27cea8526af8cfee3be5e183ac9605-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/5383c7318a3158b9bc261d0b6996f7c2-Paper.pdf">Parameterized Knowledge Transfer for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Hong Kong Polytechnic University; <br> </font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/5383c7318a3158b9bc261d0b6996f7c2-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/5d44a2b0d85aa1a4dd3f218be6422c66-Paper.pdf">Federated Reconstruction: Partially Local Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google Research</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/5d44a2b0d85aa1a4dd3f218be6422c66-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/64be20f6dd1dd46adf110cf871e3ed35-Paper.pdf">Fast Federated Learning in the Presence of Arbitrary Device Unavailability</a></td>
        <td class=xl6519452 align="center"><font size="2">Tsinghua University;<br>Princeton University;<br>MIT</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/hmgxr128/MIFA_code/">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/64be20f6dd1dd46adf110cf871e3ed35-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/692baebec3bb4b53d7ebc3b9fabac31b-Paper.pdf">FL-WBC: Enhancing Robustness against Model Poisoning Attacks in Federated Learning from a Client Perspective</a></td>
        <td class=xl6519452 align="center"><font size="2">Duke University;<br>Accenture Labs</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/jeremy313/FL-WBC">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/692baebec3bb4b53d7ebc3b9fabac31b-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/6aed000af86a084f9cb0264161e29dd3-Paper.pdf">FjORD: Fair and Accurate Federated Learning under heterogeneous targets with Ordered Dropout</a></td>
        <td class=xl6519452 align="center"><font size="2">KAUST;<br>Samsung AI Center</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/6aed000af86a084f9cb0264161e29dd3-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/6aed000af86a084f9cb0264161e29dd3-Paper.pdf">Linear Convergence in Federated Learning: Tackling Client Heterogeneity and Sparse Gradients</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Pennsylvania</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/7a6bda9ad6ffdac035c752743b7e9d0e-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/82599a4ec94aca066873c99b4c741ed8-Paper.pdf">Federated Multi-Task Learning under a Mixture of Distributions</a></td>
        <td class=xl6519452 align="center"><font size="2">INRIA;<br>Accenture Labs</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/omarfoq/FedEM">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/82599a4ec94aca066873c99b4c741ed8-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/9c6947bd95ae487c81d4e19d3ed8cd6f-Paper.pdf">Federated Graph Classification over Non-IID Graphs</a></td>
        <td class=xl6519452 align="center"><font size="2">Emory University</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/9c6947bd95ae487c81d4e19d3ed8cd6f-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/a0205b87490c847182672e8d371e9948-Paper.pdf">Federated Hyperparameter Tuning: Challenges, Baselines, and Connections to Weight-Sharing</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU;<br>Hewlett Packard Enterprise</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/mkhodak/fedex">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/a0205b87490c847182672e8d371e9948-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/ab9ebd57177b5106ad7879f0896685d4-Paper.pdf">On Large-Cohort Training for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google;<br>CMU</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/google-research/federated/tree/f4e26c1b9b47ac320e520a8b9943ea2c5324b8c2/large_cohort">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/ab9ebd57177b5106ad7879f0896685d4-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/b0ab42fcb7133122b38521d13da7120b-Paper.pdf">DeepReduce: A Sparse-tensor Communication Framework for Federated Deep Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">KAUST;<br>Columbia University;<br>University of Central Florida</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/hangxu0304/DeepReduce">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/b0ab42fcb7133122b38521d13da7120b-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/c429429bf1f2af051f2021dc92a8ebea-Paper.pdf">PartialFed: Cross-Domain Personalized Federated Learning via Partial Initialization</a></td>
        <td class=xl6519452 align="center"><font size="2">Huawei</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/c429429bf1f2af051f2021dc92a8ebea-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/ceb0595112db2513b9325a85761b7310-Paper.pdf">Federated Split Task-Agnostic Vision Transformer for COVID-19 CXR Diagnosis</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/ceb0595112db2513b9325a85761b7310-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/db8e1af0cb3aca1ae2d0018624204529-Paper.pdf">Addressing Algorithmic Disparity and Performance Inconsistency in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Tsinghua University;<br> Alibaba;<br>Weill Cornell Medicine</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/cuis15/FCFL">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/db8e1af0cb3aca1ae2d0018624204529-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/e347c51419ffb23ca3fd5050202f9c3d-Paper.pdf">Federated Linear Contextual Bandits</a></td>
        <td class=xl6519452 align="center"><font size="2">The Pennsylvania State University;<br> Facebook;<br>University of Virginia</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/e347c51419ffb23ca3fd5050202f9c3d-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/f065d878ccfb4cc4f4265a4ff8bafa9a-Paper.pdf">Few-Round Learning for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/f065d878ccfb4cc4f4265a4ff8bafa9a-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/f0e6be4ce76ccfa73c5a540d992d0756-Paper.pdf">Breaking the centralized barrier for cross-device federated learning</a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL;<br>Google Research</font></td>
        <td class=xl6519452 align="center"><a href="https://fedjax.readthedocs.io/en/latest/fedjax.algorithms.html#module-fedjax.algorithms.mime">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/f0e6be4ce76ccfa73c5a540d992d0756-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/f740c8d9c193f16d8a07d3a8a751d13f-Paper.pdf">Federated-EM with heterogeneity mitigation and variance reduction</a></td>
        <td class=xl6519452 align="center"><font size="2">Ecole Polytechnique;<br>Google Research</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/f740c8d9c193f16d8a07d3a8a751d13f-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/fc03d48253286a798f5116ec00e99b2b-Paper.pdf">Delayed Gradient Averaging: Tolerate the Communication Latency for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT;<br>Amazon;<br>Google</font></td>
        <td class=xl6519452 align="center"><a href="https://dga.hanlab.ai/">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/fe7ee8fc1959cc7214fa21c4840dff0a-Paper.pdf">FedDR – Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">University of North Carolina at Chapel Hill;<br>IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/unc-optimization/FedDR">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/fe7ee8fc1959cc7214fa21c4840dff0a-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/fa84632d742f2729dc32ce8cb5d49733-Paper.pdf">Gradient Inversion with Generative Image Prior</a></td>
        <td class=xl6519452 align="center"><font size="2">Pohang University of Science and Technology;<br>University of Wisconsin-Madison;<br>University of Washington</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/ml-postech/gradient-inversion-generative-image-prior">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/fa84632d742f2729dc32ce8cb5d49733-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
        <td rowspan=17 height=323 class=xl6519452 style='height:242.25pt' align="center"><a href="https://papers.nips.cc/paper/2020">NeurIPS 2020</a></td>
		<td class=xl6519452 align="center"><a href="https://arxiv.org/abs/2010.11425">Differentially-Private Federated Linear Bandits</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/abhimanyudubey/private_federated_linear_bandits">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1907.08059">Federated Principal Component Analysis</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Cambridge;<br>Quine Technologies</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/andylamp/federated_pca">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2005.05238">FedSplit: an algorithmic framework for fast federated optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2010.10154">Federated Bayesian Optimization via Thompson Sampling</a></td>
        <td class=xl6519452 align="center"><font size="2">NUS; MIT</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2010.02372">Lower Bounds and Optimal Algorithms for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">KAUST</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2006.08907">Robust Federated
		Learning: The Case of Affine Distribution Shifts</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Santa Barbara; MIT</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2006.04088">An Efficient Framework for Clustered Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley; DeepMind</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/jichan3751/ifca">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2020/file/ac450d10e166657ec8f93a1b65ca1b14-Paper.pdf">Distributionally Robust
		Federated Averaging</a></td>
        <td class=xl6519452 align="center"><font size="2">Pennsylvania State University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/MLOPTPSU/FedTorch">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/2006.08848">Personalized
		Federated Learning with Moreau Envelopes</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Sydney</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/CharlieDinh/pFedMe">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2002.07948">Personalized Federated
		Learning with Theoretical Guarantees: A Model-Agnostic Meta-Learning Approach</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT; UT Austin</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2007.14513">Group Knowledge
		Transfer: Federated Learning of Large CNNs at the Edge</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Southern California</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/FedML-AI/FedML/tree/master/fedml_experiments/distributed/fedgkt">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2007.07481">Tackling the Objective
		Inconsistency Problem in Heterogeneous Federated Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU;<br>Princeton University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2007.05084">Attack of the Tails:
		Yes, You Really Can Backdoor Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Wisconsin-Madison</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2006.08950">Federated Accelerated
		Stochastic Gradient Descent</a></td>
        <td class=xl6519452 align="center"><font size="2">Stanford University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/hongliny/FedAc-NeurIPS20">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2003.14053">Inverting Gradients -
		How easy is it to break privacy in federated learning?</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Siegen</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/JonasGeiping/invertinggradients">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2006.07242.pdf">Ensemble Distillation for Robust Model Fusion in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.12229.pdf">Throughput-Optimal Topology Design for Cross-Silo Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">INRIA</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/omarfoq/communication-in-cross-silo-fl">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
        <td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://papers.nips.cc/paper/2018">NeurIPS 2018</a></td>
		<td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/1805.10559.pdf">cpSGD: Communication-efficient and differentially-private distributed SGD</a></td>
		<td class=xl6519452 align="center"><font size="2">Princeton University;<br>Google</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
        <td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://papers.nips.cc/paper/2017">NeurIPS 2017</a></td>
		<td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/1705.10467.pdf">Federated Multi-Task Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">Stanford; <br> USC; <br> CMU</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/gingsmith/fmtl">code</a></td>
	</tr>
</table>

&nbsp; 


## Top Computer Vision Conferences
In this section, we will summarize Federated Learning papers accepted by top computer vision conference, Including CVPR, ICCV, ECCV.

### CVPR 
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
		<td rowspan=4 height=76 class=xl6519452 style='height:242.25pt' align="center">CVPR 2021</td>
		<td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/2103.02148.pdf">Multi-Institutional Collaborations for Improving Deep Learning-Based Magnetic Resonance Image Reconstruction Using Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Johns Hopkins University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/guopengf/FL-MRCM">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.16257.pdf">Model-Contrastive Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">National University of Singapore;<br>UC Berkeley</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/QinbinLi/MOON">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://github.com/liuquande/FedDG-ELCFS">FedDG: Federated Domain Generalization on Medical Image Segmentation via Episodic Learning in Continuous Frequency Space</a></td>
        <td class=xl6519452 align="center"><font size="2">The Chinese University of Hong Kong</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/liuquande/FedDG-ELCFS">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.06043.pdf">Soteria: Provable Defense Against Privacy Leakage in Federated Learning From Representation Perspective</a></td>
        <td class=xl6519452 align="center"><font size="2"> Duke University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/jeremy313/Soteria">code</a></td>
	</tr>
</table>

### ECCV 
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center">ECCV 2020</td>
		<td class=xl6519452 align="center"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550086.pdf">Federated Visual Classification with Real-World Data Distribution</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT;<br>Google</font></td>
		<td class=xl6519452 align="center"><a href="https://www.youtube.com/watch?v=Rc67rZzPDDY&ab_channel=TzuMingHsu">Video</a></td>
	</tr>
</table>

### ICCV 
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
		<td rowspan=2 height=38 class=xl6519452 style='height:242.25pt' align="center">ICCV 2021</td>
		<td class=xl6519452 align="center"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_Federated_Learning_for_Non-IID_Data_via_Unified_Feature_Learning_and_ICCV_2021_paper.pdf">Federated Learning for Non-IID Data via Unified Feature Learning and Optimization Objective Alignment</a></td>
        <td class=xl6519452 align="center"><font size="2">Peking University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Gong_Ensemble_Attention_Distillation_for_Privacy-Preserving_Federated_Learning_ICCV_2021_paper.pdf">Ensemble Attention Distillation for Privacy-Preserving Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University at Buffalo</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
</table>


&nbsp; 

## Top Artificial Intelligence and Data Mining Conferences

In this section, we will summarize Federated Learning papers accepted by top AI and DM conference, Including AAAI, AISTATS, KDD.

### AAAI

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td rowspan=15 height=285 class=xl6519452 style='height:85.5pt' align="center"><a href="https://aaai.org/Conferences/AAAI-22/wp-content/uploads/2021/12/AAAI-22_Accepted_Paper_List_Main_Technical_Track.pdf">AAAI 2022</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2112.10775.pdf">HarmoFL: Harmonizing Local and Global Drifts in Federated Learning on Heterogeneous Medical Images</a></td>
        <td class=xl6519452 align="center"><font size="2"> The Chinese University of Hong Kong;<br>Beihang University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/med-air/HarmoFL">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.07246.pdf">Federated Learning for Face Recognition with Gradient Correction</a></td>
        <td class=xl6519452 align="center"><font size="2">Beijing University of Posts and Telecommunications</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.02743.pdf">SpreadGNN: Decentralized Multi-Task Federated Learning for Graph Neural Networks on Molecular Data</a></td>
        <td class=xl6519452 align="center"><font size="2">university of Southern California</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/FedML-AI/SpreadGNN">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/16920">SmartIdx: Reducing Communication Cost in Federated Learning by Exploiting the CNNs Structures</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Chinese Academy of Sciences</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.08831.pdf">Bridging between Cognitive Processing Signals and Linguistic Features via a Unified Attentional Network</a></td>
        <td class=xl6519452 align="center"><font size="2">Tianjin University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2109.05613.pdf">Seizing Critical Learning Periods in Federated Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">SUNY-Binghamton University;<br>Louisiana State University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.03970.pdf">Coordinating Momenta for Cross-silo Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Pittsburgh</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.00243.pdf">FedProto: Federated Prototype Learning over Heterogeneous Devices</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Technology Sydney;<br>University of Washington</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/yuetan031/fedproto">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.06053.pdf">FedSoft: Soft Clustered Federated Learning with Proximal Local Updating</a></td>
        <td class=xl6519452 align="center"><font size="2">Carnegie Mellon University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.09824.pdf">Federated Dynamic Sparse Training: Computing Less, Communicating Less, Yet Learning Better</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Texas at Austin</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/bibikar/feddst">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.12496.pdf">FedFR: Joint Optimization Federated Framework for Generic and Personalized Face Recognition</a></td>
        <td class=xl6519452 align="center"><font size="2">National Taiwan University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/jackie840129/fedfr">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2004.12088.pdf">SplitFed: When Federated Learning Meets Split Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">CSIRO;<br>Lehigh University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/chandra2thapa/SplitFed-When-Federated-Learning-Meets-Split-Learning">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.05928.pdf">Efficient Device Scheduling with Multi-Job Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Soochow University;<br>Baidu</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.13897.pdf">Implicit Gradient Alignment in Distributed and Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">IIT Kanpur;<br>EPFL</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2112.07157.pdf">Federated Nearest Neighbor Classification with a Colony of Fruit-Flies</a></td>
        <td class=xl6519452 align="center"><font size="2">IBM Research;<br>Wichita State University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td rowspan=14 height=266 class=xl6519452 style='height:85.5pt' align="center"><a href="https://aaai.org/Conferences/AAAI-21/wp-content/uploads/2020/12/AAAI-21_Accepted-Paper-List.Main_.Technical.Track_.pdf">AAAI 2021</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2103.00958.pdf">Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating</a></td>
        <td class=xl6519452 align="center"><font size="2"> Xidian University;<br>JD Tech</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38947765/secure-bilevel-asynchronous-vertical-federated-learning-with-backward-updating">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/16546"> FedRec++: Lossless Federated Recommendation with Explicit Feedback</a></td>
        <td class=xl6519452 align="center"><font size="2">Shenzhen University</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38947798/fedrec-lossless-federated-recommendation-with-explicit-feedback">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2101.12204.pdf">Federated Multi-Armed Bandits</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Virginia</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/ShenGroup/FMAB">code</a><br><a href="https://slideslive.com/38947985/federated-multiarmed-bandits">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/16920">On the Convergence of Communication-Efficient Local SGD for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Temple University;<br>University of Pittsburgh</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38948341/on-the-convergence-of-communicationefficient-local-sgd-for-federated-learning">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2009.08063.pdf">FLAME: Differentially Private Federated Learning in the Shuffle Model</a></td>
        <td class=xl6519452 align="center"><font size="2">Renmin University of China;<br>Kyoto University</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38948496/flame-differentially-private-federated-learning-in-the-shuffle-model">video</a><br><a href="https://github.com/Rachelxuan11/FLAME">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.10936.pdf">Toward Understanding the Influence of Individual Clients in Federated Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">Shanghai Jiao Tong University;<br>The University of Texas at Dallas</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38948549/toward-understanding-the-influence-of-individual-clients-in-federated-learning">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.01854.pdf">Provably Secure Federated Learning against Malicious Clients</a></td>
        <td class=xl6519452 align="center"><font size="2">Duke University</font></td>
        <td class=xl6519452 align="center"><a href="https://www.youtube.com/watch?v=LP4uqW18yA0&ab_channel=PurdueCERIAS">video</a><br><a href="https://people.duke.edu/~zg70/code/Secure_Federated_Learning.pdf">slides</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.03797.pdf">Personalized Cross-Silo Federated Learning on Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">Simon Fraser University;<br>McMaster University</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38948676/personalized-crosssilo-federated-learning-on-noniid-data">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.00753.pdf">Model-Sharing Games: Analyzing Federated Learning under Voluntary Participation</a></td>
        <td class=xl6519452 align="center"><font size="2">Cornell University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/kpdonahue/model_sharing_games">code</a><br><a href="https://slideslive.com/38948684/modelsharing-games-analyzing-federated-learning-under-voluntary-participation">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.00655.pdf">Curse or Redemption? How Data Heterogeneity Affects the Robustness of Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Nevada;<br>IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38949098/curse-or-redemption-how-data-heterogeneity-affects-the-robustness-of-federated-learning">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/17093">Game of Gradients: Mitigating Irrelevant Clients in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">IIT Bombay;<br>IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38949109/game-of-gradients-mitigating-irrelevant-clients-in-federated-learning">video</a><br><a href="https://github.com/nlokeshiisc/SFedAvg-AAAI21">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.13900.pdf">Federated Block Coordinate Descent Scheme for Learning Global and Personalized Models</a></td>
        <td class=xl6519452 align="center"><font size="2">The Chinese University of Hong Kong;<br>Arizona State University</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38949195/federated-block-coordinate-descent-scheme-for-learning-global-and-personalized-models">video</a><br><a href="https://github.com/REIYANG/FedBCD">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2008.06217.pdf">Adressing Class Imbalance in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Northwestern University</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38949283/adressing-class-imbalance-in-federated-learning">video</a><br><a href="https://github.com/balanced-fl/Addressing-Class-Imbalance-FL">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.03767.pdf">Defending against Backdoors in Federated Learning with Robust Learning Rate</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Texas at Dallas</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38949344/defending-against-backdoors-in-federated-learning-with-robust-learning-rate">video</a><br><a href="https://github.com/TinfoilHat0/Defending-Against-Backdoors-with-Robust-Learning-Rate">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td rowspan=5 height=95 class=xl6519452 style='height:85.5pt' align="center"><a href="https://aaai.org/Conferences/AAAI-20/wp-content/uploads/2020/01/AAAI-20-Accepted-Paper-List.pdf">AAAI 2020</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1911.04206.pdf"> Practical Federated Gradient Boosting Decision Trees</a></td>
        <td class=xl6519452 align="center"><font size="2">National University of Singapore;<br> The University of Western Australia</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/Xtra-Computing/PrivML">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6824">Federated Learning for Vision-and-Language Grounding Problems</a></td>
        <td class=xl6519452 align="center"><font size="2">Peking University;<br>Tencent</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6096">Federated Latent Dirichlet Allocation: A Local Differential Privacy Based Framework</a></td>
        <td class=xl6519452 align="center"><font size="2">Beihang University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6121">Federated Patient Hashing</a></td>
        <td class=xl6519452 align="center"><font size="2">Cornell University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1905.02941.pdf">Robust Federated Learning via Collaborative Machine Teaching</a></td>
        <td class=xl6519452 align="center"><font size="2">Symantec Research Labs;<br>KAUST</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
</table>


### AISTATS

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
		<td class=xl6519452 width="65%" align="center">Title</td>
		<td class=xl6519452 width="25%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
	<tr height=19 style='height:14.25pt'>
        <td rowspan=7 height=133 class=xl6519452 style='height:85.5pt' align="center"><a href="http://proceedings.mlr.press/v130/">AISTATS 2021</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v130/fraboni21a/fraboni21a.pdf">Free-rider Attacks on Model Aggregation in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Accenture Labs</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/27640">video</a><br><a href="http://proceedings.mlr.press/v130/fraboni21a/fraboni21a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/zheng21a/zheng21a.pdf">Federated f-differential privacy</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Pennsylvania</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/enosair/federated-fdp">code</a><br><a href="https://papertalk.org/papertalks/27595">video</a><br><a href="http://proceedings.mlr.press/v130/zheng21a/zheng21a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/haddadpour21a/haddadpour21a.pdf">Federated learning with compression: Unified analysis and sharp guarantees</a></td>
        <td class=xl6519452 align="center"><font size="2">The Pennsylvania State University;<br>The University of Texas at Austin</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/MLOPTPSU/FedTorch">code</a><br><a href="https://papertalk.org/papertalks/27584">video</a><br><a href="http://proceedings.mlr.press/v130/haddadpour21a/haddadpour21a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/girgis21a/girgis21a.pdf">Shuffled Model of Differential Privacy in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">UCLA;<br>Google</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/27565">video</a><br><a href="http://proceedings.mlr.press/v130/girgis21a/girgis21a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/charles21a/charles21a.pdf">Convergence and Accuracy Trade-Offs in Federated Learning and Meta-Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/27559">video</a><br><a href="http://proceedings.mlr.press/v130/charles21a/charles21a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/shi21c/shi21c.pdf">Federated Multi-armed Bandits with Personalization</a></td>
		<td class=xl6519452 align="center"><font size="2">University of Virginia;<br>The Pennsylvania State University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/ShenGroup/PF_MAB">code</a><br><a href="https://papertalk.org/papertalks/27521">video</a><br><a href="http://proceedings.mlr.press/v130/shi21c/shi21c-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/ruan21a/ruan21a.pdf">Towards Flexible Device Participation in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU;<br> Sun Yat-Sen University</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/27467">video</a><br><a href="http://proceedings.mlr.press/v130/ruan21a/ruan21a-supp.pdf">Supplementary</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center"><a href="http://proceedings.mlr.press/v108/">AISTATS 2020</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v108/reisizadeh20a/reisizadeh20a.pdf">FedPAQ: A Communication-Efficient Federated Learning Method with Periodic Averaging and Quantization</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Santa Barbara;<br> UT Austin</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/7961">video</a><br><a href="http://proceedings.mlr.press/v108/reisizadeh20a/reisizadeh20a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v108/bagdasaryan20a/bagdasaryan20a.pdf">How To Backdoor Federated Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">Cornell Tech</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/8046">video</a><br><a href="https://github.com/ebagdasa/backdoor_federated_learning">code</a><br><a href="http://proceedings.mlr.press/v108/bagdasaryan20a/bagdasaryan20a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v108/zhu20a/zhu20a.pdf">Federated Heavy Hitters Discovery with Differential Privacy</a></td>
        <td class=xl6519452 align="center"><font size="2">RPI;<br>Google</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/8129">video</a><br><a href="http://proceedings.mlr.press/v108/zhu20a/zhu20a-supp.pdf">Supplementary</a></td>
	</tr>
</table>


### KDD

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Years</td>
        <td height=19 class=xl6519452 width="5%" align="center">Sessions</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
	<tr height=19 style='height:14.25pt'>
        <td rowspan=6 height=114 class=xl6519452 style='height:85.5pt' align="center"><a href="https://kdd.org/kdd2021/accepted-papers/index">KDD 2021</a></td>
        <td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Research Track</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2111.14248.pdf">Fed2: Feature-Aligned Federated Learning
</a></td>
        <td class=xl6519452 align="center"><font size="2">George Mason University;<br>Microsoft;<br>University of Maryland</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://www.lamda.nju.edu.cn/lixc/papers/FedRS-KDD2021-Lixc.pdf">FedRS: Federated Learning with Restricted Softmax for Label Distribution Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">Nanjing University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://jyhong.gitlab.io/publication/fade2021kdd/slides.pdf">Federated Adversarial Debiasing for Fair and Trasnferable Representations</a></td>
        <td class=xl6519452 align="center"><font size="2">Michigan State University</font></td>
        <td class=xl6519452 align="center"><a href="https://jyhong.gitlab.io/publication/fade2021kdd/">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://dl.acm.org/doi/pdf/10.1145/3447548.3467371">Cross-Node Federated Graph Neural Network for Spatio-Temporal Data Modeling</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Southern California</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/mengcz13/KDD2021_CNFGNN">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
        <td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Application Track</td>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2109.12519.pdf">AsySQN: Faster Vertical Federated Learning Algorithms with Better Computation Resource Utilization</a></td>
        <td class=xl6519452 align="center"><font size="2"JD Tech</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.05218.pdf">FLOP: Federated Learning on Medical Datasets using Partial Networks</a></td>
        <td class=xl6519452 align="center"><font size="2">Duke University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/jianyizhang123/FLOP">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
            <td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center"><a href="https://www.kdd.org/kdd2020/accepted-papers">KDD 2020</a></td>
        <td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Research Track</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://dl.acm.org/doi/pdf/10.1145/3394486.3403176">FedFast: Going Beyond Average for Faster Training of Federated Recommender Systems</a></td>
        <td class=xl6519452 align="center"><font size="2">University College Dublin</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/23422">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
        <td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Application Track</td>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2008.06197.pdf">Federated Doubly Stochastic Kernel Learning for Vertically Partitioned Data</a></td>
        <td class=xl6519452 align="center"><font size="2">JD Tech</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/23301">video</a></td>
	</tr>
</table>


&nbsp; 

## Books

- 联邦学习（Federated Learning）

  [Chinese Version](https://item.jd.com/12649191.html)

  [English Version](https://www.amazon.com/Federated-Learning-Synthesis-Artificial-Intelligence/dp/1681736977/ref=sr_1_1?dchild=1&keywords=federated+learning&qid=1617695403&sr=8-1)

- 联邦学习实战（Practicing Federated Learning）

  [Chinese Version](https://item.jd.com/13206070.html)
  
  [Github](https://github.com/FederatedAI/Practicing-Federated-Learning)
  

&nbsp; 

## Papers

### 1. Model Aggregation

Model Aggregation (or Model Fusion) refers to how to combine local models into a shared global model.  

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="60%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="60%" align="center">Papers</td>
		<td class=xl6519452 width="5%" align="center">Abbreviation</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1602.05629.pdf">Communication-Efficient Learning of Deep Networks from Decentralized Data</a></td>
		<td class=xl6519452 align="center">FedAvg</td>
        <td class=xl6519452 align="center">ASTATS 2017</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1905.12022.pdf">Bayesian Nonparametric Federated Learning of Neural Networks</a></td>
		<td class=xl6519452 align="center">PFNM</td>
        <td class=xl6519452 align="center">ICML 2019</td>
		<td class=xl6519452 align="center"><a href="https://github.com/IBM/probabilistic-federated-neural-matching">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://proceedings.neurips.cc/paper/2017/file/f4b9ec30ad9f68f89b29639786cb62ef-Paper.pdf">Machine Learning with Adversaries: Byzantine Tolerant Gradient Descent</a></td>
		<td class=xl6519452 align="center">Krum</td>
        <td class=xl6519452 align="center">NeurIPS 2017</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1803.01498.pdf">Byzantine-Robust Distributed Learning: Towards Optimal Statistical Rates</a></td>
		<td class=xl6519452 align="center">median;<br>trimmed mean</td>
        <td class=xl6519452 align="center">ICML 2018</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.01736.pdf">Distributed Training with Heterogeneous Data: Bridging Median- and Mean-Based Algorithms</a></td>
		<td class=xl6519452 align="center">median;<br>mean</td>
        <td class=xl6519452 align="center">NeurIPS 2020</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v80/mhamdi18a/mhamdi18a.pdf">The hidden vulnerability of distributed learning in byzantium</a></td>
		<td class=xl6519452 align="center">Bulyan</td>
        <td class=xl6519452 align="center">ICML 2018</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1805.10032.pdf">Zeno: Distributed Stochastic Gradient Descent with Suspicion-based Fault-tolerance</a></td>
		<td class=xl6519452 align="center">Zeno </td>
        <td class=xl6519452 align="center">ICML 2019</td>
		<td class=xl6519452 align="center"><a href="https://github.com/xcgoner/icml2019_zeno">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1911.00218.pdf">Statistical Model Aggregation via Parameter Matching</a></td>
		<td class=xl6519452 align="center">SPAHM</td>
        <td class=xl6519452 align="center">	NeurIPS 2019</td>
		<td class=xl6519452 align="center"><a href="https://github.com/IBM/SPAHM">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2009.06303.pdf">Fed+: A Unified Approach to Robust Personalized Federated Learning</a></td>
		<td class=xl6519452 align="center">Fed+</td>
        <td class=xl6519452 align="center"></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1812.06127.pdf">FEDERATED OPTIMIZATION IN HETEROGENEOUS NETWORKS</a></td>
		<td class=xl6519452 align="center">FedProx</td>
        <td class=xl6519452 align="center">MLSys 2020</td>
		<td class=xl6519452 align="center"><a href="https://github.com/litian96/FedProx">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.09400.pdf">Separation of Powers in Federated Learning</a></td>
		<td class=xl6519452 align="center">Truda</td>
        <td class=xl6519452 align="center"></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2009.01974.pdf">FedBE: Making Bayesian Model Ensemble Applicable to Federated Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">FedBE</font></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(The Ohio State University)</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=BkluqlSFDS">Federated Learning with Matched Averaging</a></td>
		<td class=xl6519452 align="center"><font size="2">FedMA</font></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2020<br>(University of Wisconsin-Madison; IBM)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/IBM/FedMA">Code</a></td>
	</tr>
</table>

&nbsp; 

### 2. Personalization

Personalized federated learning refers to train a model for each client, based on the client’s own dataset and the datasets of other clients. There are two major motivations for personalized federated learning：

- Due to statistical heterogeneity across clients, a single global model would not be a good choice for all clients. Sometimes, the local models trained solely on their private data perform better than the global shared model.   
- Different clients need models specifically customized to their own environment. As an example of model heterogeneity, consider the sentence: “I live in .....”. The next-word prediction task applied on this sentence needs to predict a different answer customized for each user. Different clients may assign different labels to the same data.



Personalized federated learning Survey paper:

- [Survey of Personalization Techniques for Federated Learning](https://arxiv.org/pdf/2003.08673.pdf)

- [Three Approaches for Personalization with Applications to Federated Learning](https://arxiv.org/pdf/2002.10619.pdf)

- [Personalized Federated Learning for Intelligent IoT Applications: A Cloud-Edge based Framework](https://arxiv.org/pdf/2002.10671.pdf)

  

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Methodology</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
		<td class=xl6519452 width="23%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=7 height=133 class=xl6519452 style='height:85.5pt' align="center">Multi-Task Learning</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1705.10467.pdf">Federated Multi-Task Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2017<br>(Stanford; USC; CMU)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/gingsmith/fmtl">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1610.05202.pdf">Decentralized Collaborative Learning of Personalized Models over Networks</a></td>
        <td class=xl6519452 align="center"><font size="2">AISTATS 2017<br>(INRIA)</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.06268.pdf">Variational Federated Multi-Task Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ETH Zurich</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1901.08460.pdf">Fully Decentralized Joint Learning of Personalized Models and Collaboration Graphs</a></td>
        <td class=xl6519452 align="center"><font size="2">AISTATS 2020<br>(INRIA)</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/7855">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.03797.pdf">Personalized Cross-Silo Federated Learning on Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">AAAI 2021<br>(Simon Fraser University; McMaster University; Huawei Technologies Canada)</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38948676/personalized-crosssilo-federated-learning-on-noniid-data">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.04221.pdf">Ditto: Fair and Robust Federated Learning Through Personalization</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(CMU; Facebook AI)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/litian96/ditto">code</a><br><a href="https://papertalk.org/papertalks/32646">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2108.10252.pdf">Federated Multi-Task Learning under a Mixture of Distributions</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Inria; Accenture Labs)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/omarfoq/FedEM">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=5 height=76 class=xl6519452 style='height:85.5pt' align="center">Meta Learning</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2002.07948.pdf">Personalized Federated Learning: A Meta-Learning Approach</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v139/acar21a/acar21a.pdf">Debiasing Model Updates for Improving Personalized Federated Training</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(Boston University; Arm) </font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959212/debiasing-model-updates-for-improving-personalized-federated-training">video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1909.12488.pdf">Improving Federated Learning Personalization via Model Agnostic Meta Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Washington; </br>Google</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.02717.pdf">Adaptive Gradient-Based Meta-Learning Methods</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.02717.pdf">Federated Meta-Learning with Fast Convergence and Efficient Communication</a></td>
        <td class=xl6519452 align="center"><font size="2">Huawei Noah’s Ark Lab</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Mixture of Global and Local Models</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2002.05516.pdf">Federated Learning of a Mixture of Global and Local Models</a></td>
        <td class=xl6519452 align="center"><font size="2">KAUST</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1909.12535.pdf">Federated User Representation Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Michigan<br>Facebook</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.13461.pdf">Adaptive Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">The Pennsylvania State University</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center"> Personalization Layers</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1912.00818.pdf">Federated Learning with Personalization Layers</a></td>
        <td class=xl6519452 align="center"><font size="2">Adobe Research<br>Indian Institute of Technology</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2001.01523.pdf">Think Locally, Act Globally: Federated Learning with Local and Global Representations</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU<br>University of Tokyo<br>Columbia University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2102.07078.pdf">Exploiting Shared Representations for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center">ICML 2021<br>(University of Texas at Austin;<br> University of Pennsylvania)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/lgcollins/FedRep">code</a><br><a href="https://slideslive.com/38959519/exploiting-shared-representations-for-personalized-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Transfer Learning</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1910.10252.pdf">Federated evaluation of on-device personalization</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2002.04758.pdf">Salvaging Federated Learning by Local Adaptation</a></td>
        <td class=xl6519452 align="center"><font size="2">Cornell University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1912.06733.pdf">Private Federated Learning with Domain Adaptation
</a></td>
        <td class=xl6519452 align="center"><font size="2">Oracle Labs</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/1dba3025b159cd9354da65e2d0436a31-Paper.pdf">QuPeD: Quantized Personalization via Distillation with Applications to Federated Learning</a></td>
        <td class=xl6519452 align="center">NeurIPS 2021<br>(UCLA)</td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/1dba3025b159cd9354da65e2d0436a31-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Clustering</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1910.01991.pdf">Clustered Federated Learning: Model-Agnostic Distributed Multi-Task Optimization under Privacy Constraints</a></td>
        <td class=xl6519452 align="center"><font size="2">Fraunhofer Heinrich Hertz Institute</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/felisat/clustered-federated-learning">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2006.04088.pdf">An Efficient Framework for Clustered Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley<br>DeepMind</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/jichan3751/ifca">Code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.06629.pdf">Robust Federated Learning in a Heterogeneous Environment</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=ehJqJQk9cw">Personalized Federated Learning with First Order Model Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(Stanford University; NVIDIA)</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Hypernetwork</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2103.04628.pdf">Personalized Federated Learning using Hypernetworks</a></td>
        <td class=xl6519452 align="center"><font size="2">Bar-Ilan University;<br> NVIDIA </font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/AvivSham/pFedHN">code</a><br><a href="https://avivsham.github.io/pfedhn/">HomePage</a><br><a href="https://slideslive.com/38959583/personalized-federated-learning-using-hypernetworks">video</a></td>
	</tr>
</table>

&nbsp; 

### **3. Recommender system**

Recommender system (RecSys) is widely used to solve information overload. In general, the more data RecSys use, the better the recommendation performance we can obtain. 

Traditionally, RecSys requires the data that are distributed across multiple devices to be uploaded to the central database for model training. However, due to privacy and security concerns, such directly sharing user data strategies are no longer appropriate. 

The incorporation of federated learning and RecSys is a promising approach, which can alleviate the risk of privacy leakage.

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Methodology</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
		<td class=xl6519452 width="23%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=6 height=114 class=xl6519452 style='height:85.5pt' align="center">Matrix Factorization</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1906.05108">Secure federated matrix factorization</a></td>
        <td class=xl6519452 align="center">IEEE Intelligent Systems</td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2004.04256">Federated Multi-view Matrix Factorization for Personalized Recommendations</a></td>
        <td class=xl6519452 align="center">ECML-PKDD 2020</td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38932315/federated-multiview-matrix-factorization-for-personalized-recommendations">video</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://publicatio.bibl.u-szeged.hu/18455/1/all.pdf">Decentralized Recommendation Based on Matrix Factorization: A Comparison of Gossip and Federated Learning</a></td>
        <td class=xl6519452 align="center">ECML-PKDD 2019</td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://lirias.kuleuven.be/retrieve/540896">Towards Privacy-preserving Mobile Applications with Federated Learning: The Case of Matrix Factorization</a></td>
        <td class=xl6519452 align="center">MobiSys 2019</td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1910.10086">Meta Matrix Factorization for Federated Rating Predictions</a></td>
        <td class=xl6519452 align="center">ACM SIGIR 2020</td>
        <td class=xl6519452 align="center"><a href="https://github.com/TempSDU/MetaMF">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1901.09888">Federated Collaborative Filtering for Privacy-Preserving Personalized Recommendation System</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">GNN</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2102.04925">FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"></td>
    </tr>
</table>

&nbsp; 

### **4. Security**

#### 4.1. Attack

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Methodology</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
		<td class=xl6519452 width="23%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Backdoor Attack</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1906.05108">How To Backdoor Federated Learning</a></td>
        <td class=xl6519452 align="center">AISTATS 2020</td>
    	<td class=xl6519452 align="center"><a href="https://github.com/ebagdasa/backdoor_federated_learning">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1911.07963">Can You Really Backdoor Federated Learning?</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2020/file/b8ffa41d4e492f0fad2f13e29e1762eb-Paper.pdf">Attack of the Tails: Yes, You Really Can Backdoor Federated Learning</a></td>
        <td class=xl6519452 align="center">NeurIPS 2020</td>
        <td class=xl6519452 align="center"><a href="https://github.com/ksreenivasan/OOD_Federated_Learning">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://lirias.kuleuven.be/retrieve/540896">DBA: Distributed Backdoor Attacks against Federated Learning</a></td>
        <td class=xl6519452 align="center">ICLR 2020</td>
        <td class=xl6519452 align="center"><a href="https://github.com/AI-secure/DBA">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=7 height=133 class=xl6519452 style='height:85.5pt' align="center">Gradients Attack</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1906.08935.pdf">Deep Leakage from Gradients</a></td>
        <td class=xl6519452 align="center">NeurIPS 2020</td>
    	<td class=xl6519452 align="center"><a href="https://hanlab.mit.edu/projects/dlg/">HomePage</a><br><a href="https://github.com/mit-han-lab/dlg">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.06089.pdf">Gradient Disaggregation: Breaking Privacy in Federated Learning by Reconstructing the User Participant Matrix</a></td>
        <td class=xl6519452 align="center">ICML 2021</td>
        <td class=xl6519452 align="center"><a href="https://github.com/gdisag/gradient_disaggregation">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2001.02610.pdf">iDLG: Improved Deep Leakage from Gradients</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"><a href="https://github.com/PatrickZH/Improved-Deep-Leakage-from-Gradients">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2001.02610.pdf">See through Gradients: Image Batch Recovery via GradInversion</a></td>
        <td class=xl6519452 align="center">CVPR 2021</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.14053.pdf">Inverting Gradients - How easy is it to break Privacy in Federated Learning?</a></td>
        <td class=xl6519452 align="center">NeurIPS 2020</td>
        <td class=xl6519452 align="center"><a href="https://github.com/PatrickZH/Improved-Deep-Leakage-from-Gradients">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/08040837089cdf46631a10aca5258e16-Paper.pdf">CAFE: Catastrophic Data Leakage in Vertical Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Rensselaer Polytechnic Institute; IBM)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/DeRafael/CAFE">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/08040837089cdf46631a10aca5258e16-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/3b3fff6463464959dcd1b68d0320f781-Paper.pdf">Evaluating Gradient Inversion Attacks and Defenses in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Princeton University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/JonasGeiping/invertinggradients">Code</a><br><a href="https://papers.neurips.cc/paper/2021/hash/3b3fff6463464959dcd1b68d0320f781-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=5 height=95 class=xl6519452 style='height:85.5pt' align="center">Model Poison Attack</td>
    	<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/1811.12470">Analyzing Federated Learning through an Adversarial Lens</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2019<br>(Princeton University; IBM)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/inspire-group/ModelPoisoning">Code</a></td>
    </tr>
</table>


&nbsp; 

#### 4.2. Defense

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Methodology</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
		<td class=xl6519452 width="23%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=5 height=95 class=xl6519452 style='height:85.5pt' align="center">FL+DP</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1911.00222">Federated Learning With Differential Privacy: Algorithms and Performance Analysis</a></td>
        <td class=xl6519452 align="center">IEEE Transactions on Information Forensics and Security</td>
    	<td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1712.07557">Differentially Private Federated Learning: A Client Level Perspective</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"><a href="https://github.com/SAP-samples/machine-learning-diff-private-federated-learning">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1710.06963">Learning Differentially Private Recurrent Language Models</a></td>
        <td class=xl6519452 align="center">ICLR 2018</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.06387.pdf">The Distributed Discrete Gaussian Mechanism for Federated Learning with Secure Aggregation</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(Google)</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959306/the-distributed-discrete-gaussian-mechanism-for-federated-learning-with-secure-aggregation">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/285baacbdf8fda1de94b19282acd23e2-Paper.pdf">The Skellam Mechanism for Differentially Private Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Google Research; CMU)</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/285baacbdf8fda1de94b19282acd23e2-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">FL+HE</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1711.10677">Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://www.usenix.org/system/files/atc20-zhang-chengliang.pdf">BatchCrypt: Efficient Homomorphic Encryption for Cross-Silo Federated Learning</a></td>
        <td class=xl6519452 align="center">USENIX 2020</td>
        <td class=xl6519452 align="center"><a href="https://github.com/marcoszh/BatchCrypt">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">FL+TEE</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2104.14380.pdf">PPFL: Privacy-preserving Federated Learning with Trusted Execution Environments</a></td>
        <td class=xl6519452 align="center">ACM MobiSys 2021</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2004.05703.pdf">Darknetz: towards model privacy at the edge using trusted execution environments.</a></td>
        <td class=xl6519452 align="center">ACM MobiSys 2020</td>
        <td class=xl6519452 align="center"><a href="https://github.com/mofanv/darknetz">code</a><br><a href="https://www.youtube.com/watch?v=mEAlONq3MU4&ab_channel=ACMSIGMOBILEONLINE">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Algorithm</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://papers.nips.cc/paper/9069-a-little-is-enough-circumventing-defenses-for-distributed-learning.pdf">A Little Is Enough: Circumventing Defenses For Distributed Learning</a></td>
        <td class=xl6519452 align="center">NeurIPS 2019</td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.08283.pdf">CRFL: Certifiably Robust Federated Learning against Backdoor Attacks</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(UIUC; IBM)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/AI-secure/CRFL">code</a><br><a href="https://slideslive.com/38959047/crfl-certifiably-robust-federated-learning-against-backdoor-attacks">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/3b3fff6463464959dcd1b68d0320f781-Paper.pdf">Evaluating Gradient Inversion Attacks and Defenses in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Princeton University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/JonasGeiping/invertinggradients">Code</a><br><a href="https://papers.neurips.cc/paper/2021/hash/3b3fff6463464959dcd1b68d0320f781-Abstract.html">HomePage</a></td>
	</tr>
</table>    

&nbsp; 

### **5. Survey**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Category</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=5 height=95 class=xl6519452 style='height:85.5pt' align="center">General</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1902.04885.pdf">Federated machine learning: Concept and applications</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1907.09693.pdf">A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1909.11875.pdf">Federated Learning in Mobile Edge Networks: A Comprehensive Survey</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1912.04977.pdf">Advances and Open Problems in Federated Learning</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1908.07873.pdf">Federated Learning: Challenges, Methods, and Future Directions</a></td>
    </tr>
    <tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Security</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://www.researchgate.net/publication/344611776_A_survey_on_security_and_privacy_of_federated_learning">A survey on security and privacy of federated learning</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2003.02133">Threats to Federated Learning: A Survey</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://www.semanticscholar.org/paper/Vulnerabilities-in-Federated-Learning-Bouacida-Mohapatra/4eb8c7023c57f76d5e2401c033e7e2769be03a79">Vulnerabilities in Federated Learning</a></td>
    </tr>
    <tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Personalization</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2003.08673">Survey of Personalization Techniques for Federated Learning</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.00710.pdf">Towards Personalized Federated Learning</a></td>
    </tr>
	<tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Aggregation</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2102.12920.pdf">Emerging Trends in Federated Learning: From Model Fusion to Federated X Learning</a></td>
    </tr>
	<tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Incentive</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2106.15406.pdf">A Comprehensive Survey of Incentive Mechanism for Federated Learning</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://home.ustc.edu.cn/~yxjing/C2021/A%20Survey%20of%20Incentive%20Mechanism%20Design%20for%20Federated%20Learning.pdf">A Survey of Incentive Mechanism Design for Federated Learning</a></td>
    </tr>
	<tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Applications</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2104.10501">A Survey on Federated Learning and its Applications for Accelerating Industrial Internet of Things</a></td>
    </tr>
	<tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Fairness</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2111.01872.pdf">A Survey of Fairness-Aware Federated Learning</a></td>
    </tr>
	<tr height=25 style='height:14.25pt'>
    	<td height=25 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Graph</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2104.07145.pdf">FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2105.11099.pdf">Federated Graph Learning - A Position Paper</a></td>
    </tr>
</table>

&nbsp; 

### **6. System Design**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="10%" align="center">Platform</td>
		<td class=xl6519452 width="50%" align="center">Papers</td>
		<td height=19 class=xl6519452 width="5%" align="center">Affiliations</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://www.tensorflow.org/federated">Tensorflow-Federated</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1902.01046">Towards Federated Learning at Scale: System Design</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">Google</td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/OpenMined/PySyft">PySyft</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1811.04017">A generic framework for privacy preserving deep learning</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">OpenMined</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/FedML-AI/FedML">FedML</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2007.13518">FedML: A Research Library and Benchmark for Federated Machine Learning</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://fedml.ai/">fedml.ai</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/intel/openfl">OpenFL</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2105.06413">OpenFL: An open-source framework for Federated Learning</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">Intel</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://developer.nvidia.com/clara">Clara</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">NVIDIA</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/IBM/federated-learning-lib">IBM Federated Learning</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2007.10987.pdf">IBM Federated Learning: an Enterprise Framework White Paper</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">IBM</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/FederatedAI/FATE">FATE</a></td>
        <td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://www.jmlr.org/papers/volume22/20-815/20-815.pdf">FATE: An Industrial Grade Platform for Collaborative Learning With Data Protection</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://fedai.org/">WeBank</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/bytedance/fedlearner">Fedlearner</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">Bytedance</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/adap/flower">Flower</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2104.03042.pdf">Flower: A Friendly Federated Learning Research Framework</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://flower.dev/">flower.dev</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/PaddlePaddle/PaddleFL">PaddleFL</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">Baidu</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/TalwalkarLab/leaf">LEAF </a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1812.01097.pdf">LEAF: A Benchmark for Federated Settings</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://leaf.cmu.edu/">CMU</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/OpenMined/PyVertical">PyVertical </a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2104.00489.pdf">PyVertical: A Vertical Federated Learning Framework for Multi-headed SplitNN</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">OpenMined</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://github.com/sherpaai/Sherpa.ai-Federated-Learning-Framework">Sherpa.ai Federated Learning </a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://developers.sherpa.ai/privacy-technology/overview">Sherpa.ai</a></td>
	</tr>	
</table>



&nbsp; 

### **7. Communication-Efficient**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="70%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="70%" align="center">Papers</td>
		<td class=xl6519452 width="25%" align="center">Conferences/Affiliations</td>
		<td height=19 class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://arxiv.org/pdf/2001.08600.pdf">RPN: A Residual Pooling Network for Efficient Federated Learning</a></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center">ECAI 2020<br>(WeBank)</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v119/hamer20a/hamer20a.pdf">FedBoost: A Communication-Efficient Algorithm for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(Google)</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928463/fedboost-a-communicationefficient-algorithm-for-federated-learning?ref=speaker-16993-latest">Video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://arxiv.org/pdf/1610.05492.pdf">Federated Learning: Strategies for Improving Communication Efficiency</a></td>
		<td class=xl6519452 align="center"><font size="2">arXiv<br>(Google)</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.07682.pdf">FetchSGD: Communication-Efficient Federated Learning with Sketching</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2020<br>(UC Berkeley; Johns Hopkins University; Amazon)</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928454/fetchsgd-communicationefficient-federated-learning-with-sketching">Video</a><br><a href="https://github.com/kiddyboots216/CommEfficient">Code</a></td>	
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/2002.11364">Acceleration for Compressed Gradient Descent in Distributed and Federated Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2020<br>(KAUST)</font></td>
        <td class=xl6519452 align="center"><a href="https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-19-00UTC-6191-acceleration_fo.pdf">Slide</a><br><a href="https://slideslive.com/38927921/acceleration-for-compressed-gradient-descent-in-distributed-optimization">Video</a></td>
	</tr>
</table>


&nbsp;   


### **8. Optimization**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="70%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="20%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="70%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Application Scenarios</td>
		<td class=xl6519452 width="20%" align="center">Conferences/Affiliations</td>
		<td height=19 class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://arxiv.org/pdf/2011.08474.pdf">Federated Composite Optimization</a></td>
		<td class=xl6619452 width=815 style='width:611pt' align="center">loss function contains a non-smooth regularizer</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center">ICML 2021(Google)</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://github.com/hongliny/FCO-ICML21">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.04635.pdf">Federated Deep AUC Maximization for Hetergeneous Data with a Constant Communication Complexity</a></td>
		<td class=xl6519452 align="center">Federated Deep AUC Maximization</td>
        <td class=xl6519452 align="center">ICML 2021<br>(The University of Iowa)</td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38959235/federated-deep-auc-maximization-for-hetergeneous-data-with-a-constant-communication-complexity">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.03198.pdf">Bias-Variance Reduced Local SGD for Less Heterogeneous Federated Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">Non-Convex Objective optimization</font></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(The University of Tokyo)</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959169/biasvariance-reduced-local-sgd-for-less-heterogeneous-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2004.01442.pdf">From Local SGD to Local Fixed-Point Methods for Federated Learning</a></td>
		<td class=xl6519452 align="center"> fixed-point algorithms optimization</td>
        <td class=xl6519452 align="center"><font size="2">ICML 2020<br>(Moscow Institute of Physics and Technology; KAUST)</font></td>
        <td class=xl6519452 align="center"><a href="https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-18-00UTC-6590-from_local_sgd.pdf">Slide</a><br><a href="https://slideslive.com/38928320/from-local-sgd-to-local-fixed-point-methods-for-federated-learning">Video</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center"><a href="https://openreview.net/pdf?id=B7v4QMR6Z9w">Federated Learning Based on Dynamic Regularization</a></td>
		<td class=xl6519452 align="center">In each round, the objective function for each device dynamically updates its regularizer</td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(Boston University; ARM)</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.05273.pdf">Federated Learning via Posterior Averaging: A New Perspective and Practical Algorithms</a></td>
		<td class=xl6519452 align="center">Formulate federated learning optimization as a posterior inference problem</td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(CMU; Google)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/alshedivat/fedpa">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.00295.pdf">Adaptive Federated Optimization</a></td>
		<td class=xl6519452 align="center">Federated versions of adaptive optimizers</td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(Google)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/google-research/federated/tree/master/optimization">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=6YEQUn0QICG">FedBN: Federated Learning on Non-IID Features via Local Batch Normalization</a></td> 
		<td class=xl6519452 align="center">How to uses local batch normalization to alleviate the feature shift before averaging models.</td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(Princeton University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/med-air/FedBN">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=ce6CFXBh30h">Federated Semi-Supervised Learning with Inter-Client Consistency & Disjoint Learning</a></td>
		<td class=xl6519452 align="center"><font size="1">SFederated versions of emi-Supervised Learning</font></td>
        <td class=xl6519452 align="center">ICLR 2021<br>(KAIST)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/wyjeong/FedMatch">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center"><a href="https://proceedings.neurips.cc/paper/2021/file/076a8133735eb5d7552dc195b125a454-Paper.pdf">Sageflow: Robust Federated Learning against Both Stragglers and Adversaries</a></td>
		<td class=xl6519452 align="center">Handle both stragglers (slow devices) and adversaries simultaneously</td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(KAIST)</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/076a8133735eb5d7552dc195b125a454-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/3016a447172f3045b65f5fc83e04b554-Paper.pdf">STEM: A Stochastic Two-Sided Momentum Algorithm Achieving Near-Optimal Sample and Communication Complexities for Federated Learning</a></td>
		<td class=xl6519452 align="center">Distributed stochastic non-convex optimization</td>
        <td class=xl6519452 align="center"><font size="2">University of Minnesota</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/3016a447172f3045b65f5fc83e04b554-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2103.00958.pdf">Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating</a></td>
		<td class=xl6519452 align="center"><font size="1"> Vertical Federated Learning Optimization</font></td>
        <td class=xl6519452 align="center"><font size="2"> AAAI 2021<br>(Xidian University; JD Tech)</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38947765/secure-bilevel-asynchronous-vertical-federated-learning-with-backward-updating">video</a></td>
	</tr>
</table>

&nbsp;   

### **9. Fairness**


<table border=0 cellpadding=0 cellspacing=0 >
	<col width="70%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="70%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.nips.cc/paper/2021/file/db8e1af0cb3aca1ae2d0018624204529-Paper.pdf">Addressing Algorithmic Disparity and Performance Inconsistency in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Tsinghua University; Alibaba)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/cuis15/FCFL">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/db8e1af0cb3aca1ae2d0018624204529-Abstract.html">HomePage</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.05057.pdf">Fairness-aware Agnostic Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">SDM 2021<br>(University of Arkansas)</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=ByexElSYDr">Fair Resource Allocation in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2020<br>(CMU; Facebook AI)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/litian96/fair_flearn">Code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1902.00146.pdf">Agnostic Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2019<br>(Google)</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.02447.pdf">Mitigating Bias in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">arXiv<br>(IBM)</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.04221.pdf">Ditto: Fair and Robust Federated Learning Through Personalization</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(CMU; Facebook AI)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/litian96/ditto">code</a><br><a href="https://slideslive.com/38955195/ditto-fair-and-robust-federated-learning-through-personalization">video</a></td>
	</tr>
</table>

&nbsp; 


### **10. Applications**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Applications</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
		<td class=xl6519452 width="23%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Computer Vision</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2001.06202">FedVision: An Online Visual Object Detection Platform Powered by Federated Learning</a></td>
        <td class=xl6519452 align="center">WeBank (AAAI 2020)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/FederatedAI/FedVision">code</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Nature Language Processing</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1906.04329.pdf">Federated learning for emoji prediction in a mobile keyboard</a></td>
        <td class=xl6519452 align="center">Google</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1811.03604">Federated Learning for Mobile Keyboard Prediction</a></td>
        <td class=xl6519452 align="center">Google</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1812.02903">Applied federated learning: Improving google keyboard query suggestions</a></td>
        <td class=xl6519452 align="center">Google</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1903.10635">Federated Learning Of Out-Of-Vocabulary Words</a></td>
        <td class=xl6519452 align="center">Google</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Automatic Speech Recognition </td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://www.isca-speech.org/archive/pdfs/interspeech_2020/dimitriadis20_interspeech.pdf">A Federated Approach in Training Acoustic Models</a></td>
        <td class=xl6519452 align="center">MicroSoft (INTERSPEECH 2020)</td>
        <td class=xl6519452 align="center"><a href="https://www.youtube.com/watch?v=YMRXBi8NbdM&ab_channel=KrishnaDN">Video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1911.04913.pdf">Privacy-Preserving Adversarial Representation Learning in ASR: Reality or Illusion?</a></td>
        <td class=xl6519452 align="center">INRIA (INTERSPEECH 2019)</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.15965.pdf">Training Speech Recognition Models with Federated Learning: A Quality/Cost Framework</a></td>
        <td class=xl6519452 align="center">Google (ICASSP 2021)</td>
        <td class=xl6519452 align="center"><a href="https://support.google.com/assistant/answer/10176224?hl=en#zippy=%2Chow-google-assistant-improves-with-federated-learning%2Cturn-on-federated-learning-for-the-hey-google-model%2Cturn-off-federated-learning-for-the-hey-google-model-delete-your-on-device-voice-recordings">Google Assistant Help</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.08503.pdf">Federated Evaluation and Tuning for On-Device Personalization: System Design \& Applications</a></td>
        <td class=xl6519452 align="center">Apple</td>
        <td class=xl6519452 align="center"><a href="https://syncedreview.com/2021/02/19/apple-reveals-design-of-its-on-device-ml-system-for-federated-evaluation-and-tuning/">Report</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Healthcare</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/1910.00962">Privacy-preserving Federated Brain Tumour Segmentation</a></td>
        <td class=xl6519452 align="center">NVIDIA (MICCAI MLMI 2019)</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://blog.google/technology/health/google-health-studies-app/">Advancing health research with Google Health Studies</a></td>
        <td class=xl6519452 align="center">Google</td>
        <td class=xl6519452 align="center"><a href="https://blog.google/technology/health/google-health-studies-app/">Blog</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1810.04304.pdf">Multi-institutional Deep Learning Modeling Without Sharing Patient Data: A Feasibility Study on Brain Tumor Segmentation</a></td>
        <td class=xl6519452 align="center">Intel</td>
        <td class=xl6519452 align="center"><a href="https://newsroom.intel.com/news/intel-works-university-pennsylvania-using-privacy-preserving-ai-identify-brain-tumors/#gs.9fo9sy">Blog</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Blockchain</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/abs/2002.11711">FedCoin: A Peer-to-Peer Payment System for Federated Learning</a></td>
        <td class=xl6519452 align="center">Arxiv</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/1808.03949">Blockchained On-Device Federated Learning</a></td>
        <td class=xl6519452 align="center">IEEE Communications Letters 2019</td>
        <td class=xl6519452 align="center"></td>
    </tr>
</table>



&nbsp; 

### **11. Boosting**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Category</td>
		<td class=xl6519452 width="67%" align="center">Papers</td>
		<td class=xl6519452 width="23%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Tree-Base Boosting</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1911.04206.pdf">Practical Federated Gradient Boosting Decision Trees</a></td>
        <td class=xl6519452 align="center">AAAI 2020<br>(NUS)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/Xtra-Computing/SimFL">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1901.08755.pdf">Secureboost: A lossless federated learning framework</a></td>
        <td class=xl6519452 align="center">IEEE Intelligent Systems 2021<br>(WeBank; HKUST)</td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2005.08479.pdf">Large-scale Secure XGB for Vertical Federated Learning</a></td>
        <td class=xl6519452 align="center">CIKM 2021<br>(Ant Group)</td>
        <td class=xl6519452 align="center"><a href="https://underline.io/lecture/36394-large-scale-secure-xgb-for-vertical-federated-learning">video</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
</table>



&nbsp; 

### **12. Incentive mechanism**

<table border=0 cellpadding=0 cellspacing=0 >
	<col width="70%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="70%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.03228.pdf">One for One, or All for All: Equilibria and Optimality of Collaboration in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021(Toyota; Berkeley; Cornell University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/rlphilli/Collaborative-Incentives">code</a><br><a href="https://slideslive.com/38959135/one-for-one-or-all-for-all-equilibria-and-optimality-of-collaboration-in-federated-learning">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/09a5e2a11bea20817477e0b1dfe2cc21-Paper.pdf">Optimality and Stability in Federated Learning: A Game-theoretic Approach</a></td>
        <td class=xl6519452 align="center">NeurIPS 2021<br>(Cornell University)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/kpdonahue/model_sharing_games">code</a><br><a href="https://papers.nips.cc/paper/2021/hash/09a5e2a11bea20817477e0b1dfe2cc21-Abstract.html">HomePage</a></td>
	</tr>
</table>


&nbsp;

### **13. Unsupervised Learning** 

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Category</td>
		<td class=xl6519452 width="65%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Clustering</td>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.00697.pdf">Heterogeneity for the Win: One-Shot Federated Clustering</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(CMU)</font></td>
		<td class=xl6519452 align="center"><a href="https://slideslive.com/38959380/heterogeneity-for-the-win-oneshot-federated-clustering">video</a></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center">Representations Learning</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2102.07078.pdf">Exploiting Shared Representations for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center">ICML 2021<br>(University of Texas at Austin;<br> University of Pennsylvania)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/lgcollins/FedRep">code</a><br><a href="https://slideslive.com/38959519/exploiting-shared-representations-for-personalized-federated-learning">video</a></td>
    </tr>
</table>

&nbsp;

### **14. Heterogeneity** 

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Category</td>
		<td class=xl6519452 width="65%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=9 height=171 class=xl6519452 style='height:85.5pt' align="center">Data Heterogeneity (NON-IID)</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2105.10056.pdf">Data-Free Knowledge Distillation for Heterogeneous Federated Learning</a></td>
        <td class=xl6519452 align="center">ICML 2021<br>(Michigan State University)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/zhuangdizhu/FedGen">code</a><br><a href="https://slideslive.com/38959429/datafree-knowledge-distillation-for-heterogeneous-federated-learning">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.04635.pdf">Federated Deep AUC Maximization for Hetergeneous Data with a Constant Communication Complexity</a></td>
        <td class=xl6519452 align="center">ICML 2021<br>(The University of Iowa)</td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38959235/federated-deep-auc-maximization-for-hetergeneous-data-with-a-constant-communication-complexity">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2102.07078.pdf">Exploiting Shared Representations for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center">ICML 2021<br>(University of Texas at Austin;<br> University of Pennsylvania)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/lgcollins/FedRep">code</a><br><a href="https://slideslive.com/38959519/exploiting-shared-representations-for-personalized-federated-learning">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td hclass=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1910.06378.pdf">SCAFFOLD: Stochastic Controlled Averaging for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2020<br>(EPFL; Google)</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38927610/scaffold-stochastic-controlled-averaging-for-federated-learning">Video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=jDdzh5ul-d">Achieving Linear Speedup with Partial Worker Participation in Non-IID Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(The Ohio State University)</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.01264.pdf">HeteroFL: Computation and Communication Efficient Federated Learning for Heterogeneous Clients</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(Duke University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/dem123456789/HeteroFL-Computation-and-Communication-Efficient-Federated-Learning-for-Heterogeneous-Clients">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=Ogga20D2HO-">FedMix: Approximation of Mixup under Mean Augmented Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2021<br>(KAIST)</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=HJxNAnVtDS">On the Convergence of FedAvg on Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2020<br>(Peking University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/lx10077/fedavgpy">Code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/2f2b265625d76a6704b08093c652fd79-Paper.pdf">No Fear of Heterogeneity: Classifier Calibration for Federated Learning with Non-IID Data</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(NUS; Huawei)</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/2f2b265625d76a6704b08093c652fd79-Abstract.html">HomePage</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Model Heterogeneity</td>
    	<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/2006.08848">Personalized Federated Learning with Moreau Envelopes</a></td>
        <td class=xl6519452 align="center">NeurIPS 2020<br>(The University of Sydney)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/CharlieDinh/pFedMe">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2002.05516.pdf">Federated Learning of a Mixture of Global and Local Models</a></td>
        <td class=xl6519452 align="center"><font size="2">KAUST</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2002.04758.pdf">Salvaging Federated Learning by Local Adaptation</a></td>
        <td class=xl6519452 align="center"><font size="2">Cornell University</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Device Heterogeneity</td>
		<td class=xl6519452 align="center"><a href="https://proceedings.neurips.cc/paper/2021/file/076a8133735eb5d7552dc195b125a454-Paper.pdf">Sageflow: Robust Federated Learning against Both Stragglers and Adversaries</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(KAIST)</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/076a8133735eb5d7552dc195b125a454-Abstract.html">HomePage</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v130/ruan21a/ruan21a.pdf">Towards Flexible Device Participation in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">AISTATS 2021<br>(CMU; Sun Yat-Sen University)</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/27467">video</a><br><a href="http://proceedings.mlr.press/v130/ruan21a/ruan21a-supp.pdf">Supplementary</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1903.03934.pdf">Asynchronous Federated Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">12th Annual Workshop on Optimization for Machine Learning</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
</table>

&nbsp;

### **15. Client Selection** 

<table border=0 cellpadding=0 cellspacing=0 >
	<col width="70%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="70%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.05883.pdf">Clustered Sampling: Low-Variance and Improved Representativity for Clients Selection in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2021<br>(Accenture)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/Accenture//Labs-Federated-Learning/tree/clustered_sampling">code</a><br><a href="https://slideslive.com/38959618/clustered-sampling-lowvariance-and-improved-representativity-for-clients-selection-in-federated-learning">video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2101.12204.pdf">Federated Multi-Armed Bandits</a></td>
        <td class=xl6519452 align="center">AAAI 2021<br>(University of Virginia)</td>
        <td class=xl6519452 align="center"><a href="https://github.com/ShenGroup/FMAB">code</a><br><a href="https://slideslive.com/38947985/federated-multiarmed-bandits">video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v108/reisizadeh20a/reisizadeh20a.pdf">FedPAQ: A Communication-Efficient Federated Learning Method with Periodic Averaging and Quantization</a></td>
        <td class=xl6519452 align="center"><font size="2">AISTATS 2020<br>(UC Santa Barbara; UT Austin)</font></td>
        <td class=xl6519452 align="center"><a href="https://papertalk.org/papertalks/7961">video</a><br><a href="http://proceedings.mlr.press/v108/reisizadeh20a/reisizadeh20a-supp.pdf">Supplementary</a></td>
	</tr>
</table>


&nbsp;

### **16. Graph Neural Networks** 

This section is partially refers to this repository: [Awesome-Federated-Learning-on-Graph-and-GNN-papers](https://github.com/huweibo/Awesome-Federated-Learning-on-Graph-and-GNN-papers)

<table border=0 cellpadding=0 cellspacing=0 >
	<col width="15%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="70%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="30%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="15%" align="center">Category</td>
		<td class=xl6519452 width="70%" align="center">Papers</td>
		<td class=xl6519452 width="30%" align="center">Conferences/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Knowledge Graph</td>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2010.12882.pdf">FedE: Embedding Knowledge Graphs in Federated Setting</a></td>
        <td class=xl6519452 align="center"><font size="2">arXiv<br>(Zhejiang University; Huawei)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/AnselCmy/FedE">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2011.11369.pdf">Improving Federated Relational Data Modeling via Basis Alignment and Weight Penalty</a></td>
        <td class=xl6519452 align="center"><font size="2">arXiv<br>(Antgroup)</font></td>
		<td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.07615.pdf">Differentially Private Federated Knowledge Graphs Embedding</a></td>
        <td class=xl6519452 align="center"><font size="2">CIKM 2021<br>(Beihang University)</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/HKUST-KnowComp/FKGE">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=8 height=152 class=xl6519452 style='height:85.5pt' align="center">Graph Neural Network</td>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2009.07351.pdf">Federated Dynamic GNN with Secure Aggregation</a></td>
        <td class=xl6519452 align="center"><font size="2">arXiv<br>(University of Notre Dame)</font></td>
		<td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2005.11903.pdf">Vertically Federated Graph Neural Network for Privacy-Preserving Node Classification</a></td>
        <td class=xl6519452 align="center"><font size="2">arXiv<br>(AntGroup)</font></td>
		<td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2011.03248.pdf">ASFGNN: Automated separated-federated graph neural network</a></td>
        <td class=xl6519452 align="center">arXiv<br>(AntGroup)</td>
		<td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2104.14628.pdf">Cluster-driven Graph Federated Learning over Multiple Domains</a></td>
        <td class=xl6519452 align="center">CVPR 2021<br>(Politecnico di Torino)</td>
		<td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.02743.pdf">SpreadGNN: Serverless Multi-task Federated Learning for Graph Neural Networks</a></td>
        <td class=xl6519452 align="center">AAAI 2022<br>(university of Southern California)</td>
		<td class=xl6519452 align="center"><a href="https://github.com/FedML-AI/SpreadGNN">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://dl.acm.org/doi/pdf/10.1145/3447548.3467371">Cross-Node Federated Graph Neural Network for Spatio-Temporal Data Modeling</a></td>
        <td class=xl6519452 align="center"><font size="2">KDD 2021<br>(University of Southern California)</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/mengcz13/KDD2021_CNFGNN">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://dl.acm.org/doi/pdf/10.1145/3447548.3467371">Federated Graph Classification over Non-IID Graphs</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Emory University)</font></td>
        <td class=xl6519452 align="center"><a href="https://papers.nips.cc/paper/2021/hash/9c6947bd95ae487c81d4e19d3ed8cd6f-Abstract.html">HomePage</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://papers.neurips.cc/paper/2021/file/34adeb8e3242824038aa65460a47c29e-Paper.pdf">Subgraph Federated Learning with Missing Neighbor Generation</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2021<br>(Emory University; University of British Columbia; Lehigh University)</font></td>
		<td class=xl6519452 align="center"><a href="https://papers.neurips.cc/paper/2021/hash/34adeb8e3242824038aa65460a47c29e-Abstract.html">HomePage</a></td>
	</tr>
</table>

&nbsp; 


## Google FL Workshops

 * [Google Workshop on Federated Learning and Analytics 2020](https://www.youtube.com/playlist?list=PLSIUOFhnxEiCJS8q6SYdc0944xlV_6Jbu) 
 * [Google Federated Learning workshop 2019](https://sites.google.com/view/federated-learning-2019/home) 

&nbsp; 

## Videos and Lectures

 * [TensorFlow Federated Tutorial Session](https://www.youtube.com/watch?v=JBNas6Yd30A&ab_channel=GoogleTechTalks) 
  
 * [TensorFlow Federated (TFF): Machine Learning on Decentralized Data ](https://www.youtube.com/watch?v=1YbPmkChcbo) - Google, TF Dev Summit ‘19 2019

 * [Federated Learning: Machine Learning on Decentralized Data](https://www.youtube.com/watch?v=89BGjQYA0uE) - Google, Google I/O 2019

 * [Federated Learning](https://www.youtube.com/watch?v=xJkY3ehX_MI) - Cloudera Fast Forward Labs, DataWorks Summit 2019

 * [GDPR, Data Shortage and AI](https://vimeo.com/313941621) - Qiang Yang, AAAI 2019 Invited Talk

&nbsp;  



## Tutorials and Blogs

 * [What is Federated Learning](https://blogs.nvidia.com/blog/2019/10/13/what-is-federated-learning/) - Nvidia 2019
 * [Online Federated Learning Comic](https://federated.withgoogle.com/) - Google 2019
 * [Federated Learning: Collaborative Machine Learning without Centralized Training Data](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html) - Google AI Blog 2017
 * [Go Federated with OpenFL](https://medium.com/@igor.davidyuk_98364/go-federated-with-openfl-8bc145a5ead1) - Intel 2021



&nbsp; 


## Open-Sources
 * [WeBank Federated AI Technology Enabler](https://github.com/FederatedAI/FATE)
 * [Google Tensorflow Federated](https://github.com/tensorflow/federated)
 * [OpenMined PySyft](https://github.com/OpenMined/PySyft)
 * [Baidu PaddleFL](https://github.com/PaddlePaddle/PaddleFL)
 * [FedML](https://github.com/FedML-AI/FedML)
 * [OpenFL](https://github.com/intel/openfl)

**[⬆ Return to top](#table-of-contents)**
