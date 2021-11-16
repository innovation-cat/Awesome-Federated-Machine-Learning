# Awesome Federated Machine Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
Federated Learning (FL) is a new machine learning framework, which enables multiple devices collaboratively to train a shared model without compromising data privacy and security.  

<div align=center>
<img width="700" src="images/cover.png" alt="FL"/>
</div>

This repository will continue to be collected and updated everything about federated learning materials, including research papers, conferences, blogs and beyond.



## Table of Contents

 - [Top Machine Learning conferences](#top-machine-learning-conferences)
     + [ICML](#ICML)&emsp;[ICLR](#ICLR)&emsp;[NeurIPS](#NeurIPS)   
 - [Top Computer Vision conferences](#top-cv-conferences)
     + [CVPR](#CVPR)&emsp;[ICCV](#ICCV)&emsp;[ECCV](#ECCV)   
 - [Books](#Books)
 - [Papers](#papers)
     + [Model Aggregation](#1-Model-Aggregation)<br>
	 + [Personalization](#2-Personalization)<br>
     + [Recommender system](#3-Recommender-system)<br>
	 + [Security](#4-Security)<br>
	 + [Survey](#5-Survey)<br>
	 + [System Architecture](#6-System-Design)<br>
	 + [Efficiency](#7-Communication-Efficient)<br>
	 + [Optimization](#8-Optimization)<br>
	 + [Fairness](#9-Fairness)<br>
	 + [Application](#10-Applications)
 - [Talks and Tutorials](#talks-and-tutorials)
 - [Conferences and Workshops](#conferences-and-workshops)
 - [Blogs](#blogs)
 - [Open-Sources](#open-sources)



## Top Machine Learning conferences

In this section, we will summarize Federated Learning papers accepted by top machine learning conference, Including Neurips, ICML, ICLR.

### ICML 
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=18 height=342 class=xl6519452 style='height:242.25pt' align="center">ICML 2021</td>
        <td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/2106.06089.pdf">Gradient Disaggregation: Breaking Privacy in Federated Learning by Reconstructing the User Participant Matrix</a></td>
        <td class=xl6519452 align="center"><font size="2">Harvard University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/gdisag/gradient_disaggregation">code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.05001.pdf">FL-NTK: A Neural Tangent Kernel-based Framework for Federated Learning Analysis</a></td>
        <td class=xl6519452 align="center"><font size="2">Peking University; Yale University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.04628.pdf">Personalized Federated Learning using Hypernetworks</a></td>
        <td class=xl6519452 align="center"><font size="2">Bar-Ilan University; NVIDIA Research</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/AvivSham/pFedHN">code</a><br><a href="https://avivsham.github.io/pfedhn/">materials</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2011.08474.pdf">Federated Composite Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">Stanford University; Google</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/hongliny/FCO-ICML21">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.07078.pdf">Exploiting Shared Representations for Personalized Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Texas at Austin; University of Pennsylvania</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/lgcollins/FedRep">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.10056.pdf">Data-Free Knowledge Distillation for Heterogeneous Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Michigan State University</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/zhuangdizhu/FedGen">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.03196.pdf">Federated Continual Learning with Weighted Inter-client Transfer</a></td>
        <td class=xl6519452 align="center"><font size="2">KAIST</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/wyjeong/FedWeIT">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.04635.pdf">Federated Deep AUC Maximization for Hetergeneous Data with a Constant Communication Complexity</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Iowa</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.03198.pdf">Bias-Variance Reduced Local SGD for Less Heterogeneous Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">The University of Tokyo</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2104.08776.pdf">Federated Learning of User Verification Models Without Sharing Embeddings</a></td>
        <td class=xl6519452 align="center"><font size="2">Qualcomm AI Research</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2105.05883.pdf">Clustered Sampling: Low-Variance and Improved Representativity for Clients Selection in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Accenture</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/Accenture//Labs-Federated-Learning/tree/clustered_sampling">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2012.04221.pdf">Ditto: Fair and Robust Federated Learning Through Personalization</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU; Facebook</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/litian96/ditto">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.00697.pdf">Heterogeneity for the Win: One-Shot Federated Clustering</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/metastableB/kfed/">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2102.06387.pdf">The Distributed Discrete Gaussian Mechanism for Federated Learning with Secure Aggregation</a></td>
        <td class=xl6519452 align="center"><font size="2">Google</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v139/acar21a/acar21a.pdf">Debiasing Model Updates for Improving Personalized Federated Training</a></td>
        <td class=xl6519452 align="center"><font size="2">Boston University; Arm Research</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2103.03228.pdf">One for One, or All for All: Equilibria and Optimality of Collaboration in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Toyota Technological Institute of Chicago; University of California, Berkeley; Cornell University</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2106.08283.pdf">CRFL: Certifiably Robust Federated Learning against Backdoor Attacks</a></td>
        <td class=xl6519452 align="center"><font size="2">University of Illinois at Urbana-Champaign; IBM Research; Zhejiang University</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/AI-secure/CRFL">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://assets.amazon.science/11/23/3e0cfaf1456d80ecf3f37a2cd812/federated-learning-under-arbitrary-communication-patterns.pdf">Federated Learning under Arbitrary Communication Patterns</a></td>
        <td class=xl6519452 align="center"><font size="2">Indiana University, Bloomington; Amazon</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=6 height=114 class=xl6519452 style='height:85.5pt' align="center">ICML 2020</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://proceedings.icml.cc/static/paper_files/icml/2020/5967-Paper.pdf">FedBoost: A Communication-Efficient Algorithm for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google Research</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928463/fedboost-a-communicationefficient-algorithm-for-federated-learning?ref=speaker-16993-latest">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2007.07682">FetchSGD:
		Communication-Efficient Federated Learning with Sketching</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley;<br>Johns Hopkins University;<br>Amazon</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928454/fetchsgd-communicationefficient-federated-learning-with-sketching">Video</a><br><a href="https://github.com/kiddyboots216/CommEfficient">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1910.06378.pdf">SCAFFOLD: Stochastic
		Controlled Averaging for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL;<br>Google Research</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38927610/scaffold-stochastic-controlled-averaging-for-federated-learning">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2004.10342">Federated Learning with
		Only Positive Labels</a></td>
        <td class=xl6519452 align="center"><font size="2">Google Research</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928322/federated-learning-with-only-positive-labels">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2004.01442.pdf">From Local SGD to Local
		Fixed-Point Methods for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Moscow Institute of Physics and Technology;<br>KAUST</font></td>
        <td class=xl6519452 align="center"><a href="https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-18-00UTC-6590-from_local_sgd.pdf">Slide</a><br><a href="https://slideslive.com/38928320/from-local-sgd-to-local-fixed-point-methods-for-federated-learning">Video</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/2002.11364">Acceleration
		for Compressed Gradient Descent in Distributed and Federated Optimization</a></td>
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
		<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">ICML 2019</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1905.12022.pdf">Bayesian Nonparametric Federated Learning of Neural Networks</a></td>
        <td class=xl6519452 align="center"><font size="2">IBM Research</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/IBM/probabilistic-federated-neural-matching">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/1811.12470">Analyzing Federated Learning through an Adversarial Lens</a></td>
        <td class=xl6519452 align="center"><font size="2">Princeton University;<br>IBM Research</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/inspire-group/ModelPoisoning">Code</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/pdf/1902.00146.pdf">Agnostic Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Google Research</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
</table>

### ICLR

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=10 height=190 class=xl6519452 style='height:242.25pt' align="center">ICLR 2021</td>
		<td class=xl6519452 align="center"><a href="https://openreview.net/pdf?id=B7v4QMR6Z9w">Federated Learning Based on Dynamic Regularization</a></td>
        <td class=xl6519452 align="center"><font size="2">Boston University; ARM</font></td>
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
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://openreview.net/pdf?id=rJgqMRVYvr">Differentially Private Meta-Learning
</a></td>
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
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
		<td rowspan=17 height=323 class=xl6519452 style='height:242.25pt' align="center">NeurIPS 2020</td>
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
        <td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2005.05238">FedSplit: an algorithmic framework for fast federated optimization</aa></td>
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
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2006.07242">Ensemble Distillation
		for Robust Model Fusion in Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">EPFL</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2010.12229">Throughput-Optimal
		Topology Design for Cross-Silo Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">INRIA</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/omarfoq/communication-in-cross-silo-fl">code</a></td>
	</tr>
</table>

### Others

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>	
	<tr height=19 style='height:14.25pt'>
		<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">AISTATS 2020</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v108/reisizadeh20a/reisizadeh20a.pdf">FedPAQ: A Communication-Efficient Federated Learning Method with Periodic Averaging and Quantization</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Santa Barbara; UT Austin</font></td>
        <td class=xl6519452 align="center"><a href="http://proceedings.mlr.press/v108/reisizadeh20a/reisizadeh20a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v108/bagdasaryan20a/bagdasaryan20a.pdf">How To Backdoor Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Cornell Tech</font></td>
        <td class=xl6519452 align="center"><a href="http://proceedings.mlr.press/v108/bagdasaryan20a/bagdasaryan20a-supp.pdf">Supplementary</a></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="http://proceedings.mlr.press/v108/zhu20a/zhu20a.pdf">Federated Heavy Hitters Discovery with Differential Privacy</a></td>
        <td class=xl6519452 align="center"><font size="2">RPI;<br>Google</font></td>
        <td class=xl6519452 align="center"><a href="http://proceedings.mlr.press/v108/zhu20a/zhu20a-supp.pdf">Supplementary</a></td>
	</tr>
</table>

## Top CV conferences
In this section, we will summarize Federated Learning papers accepted by top computer vision conference, Including CVPR, ICCV, ECCV.

### CVPR 
<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
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
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
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
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Conferences</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Affiliation</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
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


## Books

- 联邦学习（Federated Learning）

  [Chinese Version](https://item.jd.com/12649191.html)

  [English Version](https://www.amazon.com/Federated-Learning-Synthesis-Artificial-Intelligence/dp/1681736977/ref=sr_1_1?dchild=1&keywords=federated+learning&qid=1617695403&sr=8-1)

- 联邦学习实战（Practicing Federated Learning）

  [Chinese Version](https://item.jd.com/13206070.html)
  
  [Github](https://github.com/FederatedAI/Practicing-Federated-Learning)
  
  
## Papers

### 1. Model Aggregation

Model Aggregation (or Model Fusion) refers to how to combine local models into a shared global model.  

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032;width:95pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="60%" align="center">Title</td>
		<td class=xl6519452 width="5%" align="center">Abbreviation</td>
		<td class=xl6519452 width="20%" align="center">Conferences</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>	
    <tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1602.05629.pdf">Communication-Efficient Learning of Deep Networks from Decentralized Data</a></td>
		<td class=xl6519452 align="center">FedAvg</td>
        <td class=xl6519452 align="center">ASTATS 2017</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1905.12022.pdf">Bayesian Nonparametric Federated Learning of Neural Networks</a></td>
		<td class=xl6519452 align="center">PFNM</td>
        <td class=xl6519452 align="center">ICML 2019</td>
		<td class=xl6519452 align="center"><a href="https://github.com/IBM/probabilistic-federated-neural-matching">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://proceedings.neurips.cc/paper/2017/file/f4b9ec30ad9f68f89b29639786cb62ef-Paper.pdf">Machine Learning with Adversaries: Byzantine Tolerant Gradient Descent</a></td>
		<td class=xl6519452 align="center">Krum</td>
        <td class=xl6519452 align="center">NeurIPS 2017</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1803.01498.pdf">Byzantine-Robust Distributed Learning: Towards Optimal Statistical Rates</a></td>
		<td class=xl6519452 align="center">median;<br>trimmed mean</td>
        <td class=xl6519452 align="center">ICML 2018</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1906.01736.pdf">Distributed Training with Heterogeneous Data: Bridging Median- and Mean-Based Algorithms</a></td>
		<td class=xl6519452 align="center">median;<br>mean</td>
        <td class=xl6519452 align="center">NeurIPS 2020</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="http://proceedings.mlr.press/v80/mhamdi18a/mhamdi18a.pdf">The hidden vulnerability of distributed learning in byzantium</a></td>
		<td class=xl6519452 align="center">Bulyan</td>
        <td class=xl6519452 align="center">ICML 2018</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1805.10032.pdf">Zeno: Distributed Stochastic Gradient Descent with Suspicion-based Fault-tolerance</a></td>
		<td class=xl6519452 align="center">Zeno </td>
        <td class=xl6519452 align="center">ICML 2019</td>
		<td class=xl6519452 align="center"><a href="https://github.com/xcgoner/icml2019_zeno">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1911.00218.pdf">Statistical Model Aggregation via Parameter Matching</a></td>
		<td class=xl6519452 align="center">SPAHM</td>
        <td class=xl6519452 align="center">	NeurIPS 2019</td>
		<td class=xl6519452 align="center"><a href="https://github.com/IBM/SPAHM">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/2009.06303.pdf">Fed+: A Unified Approach to Robust Personalized Federated Learning</a></td>
		<td class=xl6519452 align="center">Fed+</td>
        <td class=xl6519452 align="center"></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/1812.06127.pdf">FEDERATED OPTIMIZATION IN HETEROGENEOUS NETWORKS</a></td>
		<td class=xl6519452 align="center">FedProx</td>
        <td class=xl6519452 align="center">MLSys 2020</td>
		<td class=xl6519452 align="center"><a href="https://github.com/litian96/FedProx">code</a></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td rowspan=1 height=19 class=xl6519452 style='height:242.25pt' align="center"><a href="https://arxiv.org/pdf/2105.09400.pdf">Separation of Powers in Federated Learning</a></td>
		<td class=xl6519452 align="center">Truda</td>
        <td class=xl6519452 align="center"></td>
		<td class=xl6519452 align="center"></td>
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
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Conferences</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>
<tr height=19 style='height:14.25pt'>
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Multi-Task Learning</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1903.03934.pdf">Federated Multi-Task Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Stanford<br>USC<br>CMU</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.06268.pdf">Variational Federated Multi-Task Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">ETH Zurich</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td rowspan=4 height=76 class=xl6519452 style='height:85.5pt' align="center">Meta Learning</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/2002.07948.pdf">Personalized Federated Learning: A Meta-Learning Approach</a></td>
        <td class=xl6519452 align="center"><font size="2">MIT</font></td>
        <td class=xl6519452 align="center"></td>
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
    	<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center"> Personalization Layers</td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1912.00818.pdf">Federated Learning with Personalization Layers</a></td>
        <td class=xl6519452 align="center"><font size="2">Adobe Research<br>Indian Institute of Technology</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2001.01523.pdf">Think Locally, Act Globally: Federated Learning with Local and Global Representations</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU<br>University of Tokyo<br>Columbia University
</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Transfer Learning</td>
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
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Clustering</td>
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
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1906.06629.pdf">Robust Federated Learning in a Heterogeneous
Environment</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley</font></td>
        <td class=xl6519452 align="center"></td>
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
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Conferences</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
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
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Conferences</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
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
</table>


&nbsp; 

#### 4.2. Defense

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Methodology</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Conferences</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
	</tr>
<tr height=19 style='height:14.25pt'>
    	<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">FL+DP</td>
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
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://www.usenix.org/system/files/atc20-zhang-chengliang.pdf">BatchCrypt: Efficient Homomorphic
Encryption for Cross-Silo Federated Learning</a></td>
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
    	<td rowspan=1 height=19 class=xl6519452 style='height:85.5pt' align="center"></td>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://papers.nips.cc/paper/9069-a-little-is-enough-circumventing-defenses-for-distributed-learning.pdf">A Little Is Enough: Circumventing Defenses For Distributed Learning</a></td>
        <td class=xl6519452 align="center">NeurIPS 2019</td>
        <td class=xl6519452 align="center"></td>
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
		<td class=xl6519452 width="67%" align="center">Title</td>
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
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2003.02133">Threats to Federated Learning: A Survey</a></td>
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
</table>

&nbsp; 

### **6. System Design**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="10%" align="center">Project</td>
		<td class=xl6519452 width="50%" align="center">Paper</td>
		<td height=19 class=xl6519452 width="5%" align="center">Affiliation</td>
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
    	<td class=xl6619452 width=815 style='width:611pt' align="center"></td>
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
 * [RPN: A Residual Pooling Network for Efficient Federated Learning](https://arxiv.org/abs/2001.08600) - ECAI 2020

 * [Federated Learning: Strategies for Improving Communication Efficiency](https://arxiv.org/abs/1610.05492) - arXiv 2017

&nbsp;   


### **8. Optimization**
 * [Federated Learning with Matched Averaging](https://openreview.net/forum?id=BkluqlSFDS) - ICLR 2020

 * [One-Shot Federated Learning](https://arxiv.org/abs/1902.11175) - arXiv 2019

 * [cpSGD: Communication-efficient and differentially-private distributed SGD](https://arxiv.org/abs/1805.10559) - NeurIPS 2018

 * [Federated Optimization: Distributed Machine Learning for On-Device Intelligence](https://arxiv.org/abs/1610.02527) - arXiv 2016

&nbsp;   

### **9. Fairness**
 * [Mitigating Bias in Federated Learning](https://arxiv.org/pdf/2012.02447.pdf)
 
 * [Fair Resource Allocation in Federated Learning](https://arxiv.org/abs/1905.10497) - arXiv 2019

 * [Agnostic Federated Learning](https://arxiv.org/abs/1902.00146) - ICML 2019

   

&nbsp; 


### **10. Applications**

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848;width:161pt'>
	<col width="67%" style='mso-width-source:userset;mso-width-alt:26080;width:611pt'>
	<col width="23%" style='mso-width-source:userset;mso-width-alt:10944;width:257pt'>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 width="5%" align="center">Applications</td>
		<td class=xl6519452 width="67%" align="center">Title</td>
		<td class=xl6519452 width="23%" align="center">Company</td>
		<td class=xl6519452 width="5%" align="center">Slide<br>&<br>Code</td>
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


## Talks and Tutorials

 * [TensorFlow Federated (TFF): Machine Learning on Decentralized Data ](https://www.youtube.com/watch?v=1YbPmkChcbo) - Google, TF Dev Summit ‘19 2019

 * [Federated Learning: Machine Learning on Decentralized Data](https://www.youtube.com/watch?v=89BGjQYA0uE) - Google, Google I/O 2019

 * [Federated Learning](https://www.youtube.com/watch?v=xJkY3ehX_MI) - Cloudera Fast Forward Labs, DataWorks Summit 2019

 * [GDPR, Data Shortage and AI](https://vimeo.com/313941621) - Qiang Yang, AAAI 2019 Invited Talk

 * [Making every phone smarter with Federated Learning](https://www.youtube.com/watch?v=gbRJPa9d-VU) - Google, 2018

&nbsp;  

## Conferences and Workshops

 * [FL-ICML 2020](http://federated-learning.org/fl-icml-2020/) - Organized by IBM Watson Research.
 * [FL-IBM 2020](https://federated-learning.bitbucket.io/ibm2020/) - Organized by IBM Watson Research and Webank.
 * [FL-NeurIPS 2019](http://federated-learning.org/fl-neurips-2019/) - Organized by Google, Webank, NTU, CMU.
 * [FL-IJCAI 2019](https://www.ijcai19.org/workshops.html) - Organized by Webank.
 * [Google Federated Learning workshop](https://sites.google.com/view/federated-learning-2019/home) - Organized by Google.

&nbsp; 

## Blogs

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
