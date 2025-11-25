---
title: "Robust whole slide image analysis for cervical cancer screening using deep learning"
collection: publications
category: manuscripts
permalink: /publication/robust_wsi
excerpt: 'Leveraging a multi-resolution deep learning approach, this paper presents a robust and scalable system for cervical cancer screening that achieves over 95% sensitivity on multi-center whole slide images (WSIs) with an efficient processing time of about 1.5 minutes per giga-pixel slide.'
date: 2021-09-24
venue: 'Nature Communications'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.nature.com/articles/s41467-021-25296-x'
pdfurl: 'https://www.nature.com/articles/s41467-021-25296-x.pdf'
codeurl: 'https://github.com/ShenghuaCheng/Aided-Diagnosis-System-for-Cervical-Cancer-Screening'
deployurl: 'https://github.com/hanxiaowein1/rnnPredict'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
authors: 'Shenghua Cheng#, Sibo Liu#, Jingya Yu#, Gong Rao, Yuwei Xiao, <strong>Wei Han</strong>, Wenjie Zhu, Xiaohua Lv, Ning Li, Jing Cai, Zehua Wang, Xi Feng, Fei Yang, Xiebo Geng, Jiabo Ma, Xu Li, Ziquan Wei, Xueying Zhang, Tingwei Quan, Shaoqun Zeng, Li Chen, Junbo Hu & Xiuli Liu.'
---
Computer-assisted diagnosis is key for scaling up cervical cancer screening. However, current recognition algorithms perform poorly on whole slide image (WSI) analysis, fail to generalize for diverse staining and imaging, and show sub-optimal clinical-level verification. Here, we develop a progressive lesion cell recognition method combining low- and high-resolution WSIs to recommend lesion cells and a recurrent neural network-based WSI classification model to evaluate the lesion degree of WSIs. We train and validate our WSI analysis system on 3,545 patient-wise WSIs with 79,911 annotations from multiple hospitals and several imaging instruments. On multi-center independent test sets of 1,170 patient-wise WSIs, we achieve 93.5% Specificity and 95.1% Sensitivity for classifying slides, comparing favourably to the average performance of three independent cytopathologists, and obtain 88.5% true positive rate for highlighting the top 10 lesion cells on 447 positive slides. After deployment, our system recognizes a one giga-pixel WSI in about 1.5 min.