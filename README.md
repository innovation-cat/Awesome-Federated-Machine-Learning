# Awesome Federated Machine Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
Federated Learning (FL) is a new machine learning framework, which enables multiple devices collaboratively to train a shared model without compromising data privacy and security.  

<div align=center>
<img width="700" src="images/cover.png" alt="FL"/>
</div>

This repository will continue to be collected and updated everything about federated learning materials, including research papers, conferences, blogs and beyond.



## Table of Contents

 - [Top Machine Learning conferences](#top-machine-learning-conferences)
 - [Books](#Books)
 - [Talks and Tutorials](#talks-and-tutorials)
 - [Conferences and Workshops](#conferences-and-workshops)
 - [Blogs](#blogs)
 - [Papers](#papers)
 - [Open-Sources](#open-sources)



## Top Machine Learning conferences


In this section, we will summarize Federated Learning papers accepted by top machine learning conference, Including Neurips, ICML, ICLR.
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
		<td class=xl6519452 align="center"></td>
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
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt'></td>
		<td class=xl6519452></td>
		<td class=xl6519452></td>
        <td class=xl6519452></td>
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



## Books

- 联邦学习（Federated Learning）

  [Chinese Version](https://item.jd.com/12649191.html)

  [English Version](https://www.amazon.com/Federated-Learning-Synthesis-Artificial-Intelligence/dp/1681736977/ref=sr_1_1?dchild=1&keywords=federated+learning&qid=1617695403&sr=8-1)

- 联邦学习实战（Practicing Federated Learning）

  [Chinese Version](https://item.jd.com/13206070.html)
  
  [Github](https://github.com/FederatedAI/Practicing-Federated-Learning)
  
  

## Talks and Tutorials

 * [TensorFlow Federated (TFF): Machine Learning on Decentralized Data ](https://www.youtube.com/watch?v=1YbPmkChcbo) - Google, TF Dev Summit ‘19 2019

 * [Federated Learning: Machine Learning on Decentralized Data](https://www.youtube.com/watch?v=89BGjQYA0uE) - Google, Google I/O 2019

 * [Federated Learning](https://www.youtube.com/watch?v=xJkY3ehX_MI) - Cloudera Fast Forward Labs, DataWorks Summit 2019

 * [GDPR, Data Shortage and AI](https://vimeo.com/313941621) - Qiang Yang, AAAI 2019 Invited Talk

 * [Making every phone smarter with Federated Learning](https://www.youtube.com/watch?v=gbRJPa9d-VU) - Google, 2018

   

## Conferences and Workshops

 * [FL-ICML 2020](http://federated-learning.org/fl-icml-2020/) - Organized by IBM Watson Research.
 * [FL-IBM 2020](https://federated-learning.bitbucket.io/ibm2020/) - Organized by IBM Watson Research and Webank.
 * [FL-NeurIPS 2019](http://federated-learning.org/fl-neurips-2019/) - Organized by Google, Webank, NTU, CMU.
 * [FL-IJCAI 2019](https://www.ijcai19.org/workshops.html) - Organized by Webank.
 * [Google Federated Learning workshop](https://sites.google.com/view/federated-learning-2019/home) - Organized by Google.



## Blogs

 * [What is Federated Learning](https://blogs.nvidia.com/blog/2019/10/13/what-is-federated-learning/) - Nvidia 2019
 * [Online Federated Learning Comic](https://federated.withgoogle.com/) - Google 2019
 * [Federated Learning: Collaborative Machine Learning without Centralized Training Data](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html) - Google AI Blog 2017



## Papers

### 1.  Personalization

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
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a https://arxiv.org/pdf/1906.02717.pdf">Adaptive Gradient-Based Meta-Learning Methods</a></td>
        <td class=xl6519452 align="center"><font size="2">CMU</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
    <tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a https://arxiv.org/pdf/1906.02717.pdf">Federated Meta-Learning with Fast Convergence and Efficient Communication</a></td>
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
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2003.13461.pdff">Adaptive Personalized Federated Learning</a></td>
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
		<td rowspan=2 height=38 class=xl6519452 style='height:85.5pt' align="center">Clustering</td>
		<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="https://arxiv.org/pdf/1910.01991.pdf">Clustered Federated Learning: Model-Agnostic Distributed Multi-Task Optimization under Privacy Constraints</a></td>
        <td class=xl6519452 align="center"><font size="2"></font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
    <tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2006.04088.pdf">An Efficient Framework for Clustered Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">UC Berkeley<br>DeepMind</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
</table>




### **2. Federated Learning Survey**
 * [Advances and Open Problems in Federated Learning](https://arxiv.org/abs/1912.04977) - arXiv Dec 2019

 * [A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/abs/1907.09693)  - arXiv Apr 2020

 * [Federated Learning in Mobile Edge Networks: A Comprehensive Survey](https://arxiv.org/abs/1909.11875) - arXiv Sep 2019

 * [Federated Learning for Wireless Communications: Motivation, Opportunities and Challenges](https://arxiv.org/abs/1908.06847) - arXiv Sep 2019

 * [Federated Learning: Challenges, Methods, and Future Directions](https://arxiv.org/abs/1908.07873) - arXiv Aug 2019 

 * [Federated Machine Learning: Concept and Applications](https://arxiv.org/abs/1902.04885) - ACM TIST 2018

   

### **3. System Design**
 * [Towards Federated Learning at Scale: System Design](https://arxiv.org/abs/1902.01046) - SysML 2019

 * [A generic framework for privacy preserving deep learning](https://arxiv.org/abs/1811.04017) - arXiv 2018

 * [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629) - AISTATS 2017 （The first paper proposed federated learning concept）

   

### **4. Security**

#### 4.1. Attack
 * [DBA: Distributed Backdoor Attacks against Federated Learning](https://openreview.net/forum?id=rkgyS0VFvr) - ICLR 2020

 * [Can You Really Backdoor Federated Learning?](https://arxiv.org/abs/1911.07963) - arXiv Dec 2019

 * [Analyzing Federated Learning through an Adversarial Lens](https://arxiv.org/abs/1811.12470) - ICML 2019

 * [How To Backdoor Federated Learning](https://arxiv.org/abs/1807.00459) - arXiv 2018

   

#### 4.2. Denfense
 * [A Little Is Enough: Circumventing Defenses For Distributed Learning](https://papers.nips.cc/paper/9069-a-little-is-enough-circumventing-defenses-for-distributed-learning.pdf) - NeurIPS 2019	

   

#### 4.3. Federated Learning with DP
 * [Federated Learning with Differential Privacy: Algorithms and Performance Analysis](https://arxiv.org/abs/1911.00222) - IEEE 2020

 * [Differentially Private Federated Learning: A Client Level Perspective](https://arxiv.org/abs/1712.07557v2) - arXiv 2018

 * [Learning Differentially Private Recurrent Language Models ](https://openreview.net/pdf?id=BJ0hF1Z0b) - ICLR 2018

   

#### 4.4. Federated Learning with HE
 * [Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption](https://arxiv.org/abs/1711.10677) - arXiv 2017

   


### **5. Communication-Efficient**
 * [RPN: A Residual Pooling Network for Efficient Federated Learning](https://arxiv.org/abs/2001.08600) - ECAI 2020

 * [Federated Learning: Strategies for Improving Communication Efficiency](https://arxiv.org/abs/1610.05492) - arXiv 2017

   


### **6. Optimization**
 * [Federated Learning with Matched Averaging](https://openreview.net/forum?id=BkluqlSFDS) - ICLR 2020

 * [One-Shot Federated Learning](https://arxiv.org/abs/1902.11175) - arXiv 2019

 * [cpSGD: Communication-efficient and differentially-private distributed SGD](https://arxiv.org/abs/1805.10559) - NeurIPS 2018

 * [Federated Optimization: Distributed Machine Learning for On-Device Intelligence](https://arxiv.org/abs/1610.02527) - arXiv 2016

   

### **7. Fairness**
 * [Fair Resource Allocation in Federated Learning](https://arxiv.org/abs/1905.10497) - arXiv 2019

 * [Agnostic Federated Learning](https://arxiv.org/abs/1902.00146) - ICML 2019

   

### **8. Personalization**
 * [Adaptive Personalized Federated Learning](https://arxiv.org/abs/2003.13461) - arXiv 2020

 * [Three Approaches for Personalization with Applications to Federated Learning](https://arxiv.org/abs/2002.10619) - arXiv 2020

 * [Survey of Personalization Techniques for Federated Learning](https://arxiv.org/abs/2003.08673) - arXiv 2020

 * [Survey of Personalization Techniques for Federated Learning](https://arxiv.org/abs/2003.08673) - arXiv 2020

   


### **9. Application**

#### 9.1. Computer Vision
 * [FedVision: An Online Visual Object Detection Platform Powered by Federated Learning](https://arxiv.org/abs/2001.06202) - IAAI 2020

   

#### 9.2. Nature Language Processing
 * [Federated Topic Modeling](https://dl.acm.org/doi/10.1145/3357384.3357909) - CIKM 2019

 * [Federated Learning for Mobile Keyboard Prediction](https://arxiv.org/abs/1811.03604) - arXiv 2019

 * [Applied federated learning: Improving google keyboard query suggestions](https://arxiv.org/abs/1812.02903) - arXiv 2018

 * [Federated Learning Of Out-Of-Vocabulary Words](https://arxiv.org/abs/1903.10635) - arXiv 2018

   

#### 9.3. Healthcare
 * [Privacy-preserving Federated Brain Tumour Segmentation](https://arxiv.org/abs/1910.00962) - MICCAI MLMI 2019
 * [FedHealth: A Federated Transfer Learning Framework for Wearable Healthcare](https://arxiv.org/abs/1907.09173) - arXiv 2019



#### 9.4. Recommendation
 * [Secure Federated Matrix Factorization](https://arxiv.org/abs/1906.05108) - arXiv 2019

 * [Federated Collaborative Filtering for Privacy-Preserving Personalized Recommendation System](https://arxiv.org/abs/1901.09888) - arXiv 2019

 * [Federated Meta-Learning with Fast Convergence and Efficient Communication](https://arxiv.org/abs/1802.07876) - arXiv 2018

   


#### 9.5. Blockchain

 * [FedCoin: A Peer-to-Peer Payment System for Federated Learning](https://arxiv.org/abs/2002.11711) - arXiv Feb 2020
 * [Blockchained On-Device Federated Learning](https://arxiv.org/abs/1808.03949) - IEEE Communications Letters 2019



## Open-Sources
 * [WeBank Federated AI Technology Enabler](https://github.com/FederatedAI/FATE)
 * [Google Tensorflow Federated](https://github.com/tensorflow/federated)
 * [OpenMined PySyft](https://github.com/OpenMined/PySyft)
 * [Baidu PaddleFL](https://github.com/PaddlePaddle/PaddleFL)

**[⬆ Return to top](#table-of-contents)**