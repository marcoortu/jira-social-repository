# jira-social-repository
Dataset extracted from the Jira ITS of four popular open source ecosystems i.e., the Apache Software Foundation, Spring, JBoss and CodeHaus communities.

# Overview of Data
This paper presents a dataset extracted from the Jira ITS of four popular open source ecosystems (as well as the tools and infrastructure used for extraction) the Apache Software Foundation, Spring, JBoss and CodeHaus communities. The dataset hosts more than 1K projects, containing more than 700K issue reports and more than 2 million issue comments. Using this data, the authors have been able to deeply study the communication process among developers, and how this aspect affects the development process. Furthermore, comments posted by developers contain not only technical information, but also valuable information about sentiments and emotions. The full dataset (comprising the Apache projects) hosts 3516 tasks, 16173 les and 25306 comments by 1375 authors.

# Abstract
Issue tracking systems store valuable data for testing hypotheses concerning maintenance, building statistical prediction models and the social interactions of developers when interacting with peers. In particular, the Jira Issue Tracking System (ITS) is a proprietary tracking system that has gained a tremendous popularity in the last years and offers unique features like a project management system and the Jira agile kanban board. This paper presents a dataset extracted from the Jira ITS of four popular open source ecosystems (as well as the tools and infrastructure used for extraction), i.e., the Apache Software Foundation, Spring, JBoss and CodeHaus communities. Our dataset hosts more than 1K projects, containing more than 700K issue reports and more than 2 million issue comments. Using this data, we have been able to deeply study the communication process among developers, and how this aspect aspects the development process. For example, we found that comments posted by developers contain not only technical information, but also valuable information about sentiments and emotions. With this repository we would like to encourage further studies in these directions.

# Installation

Just run ./extract.sh to generate emotion_dataset_jira.sql file or download tar.gz from [here](https://www.dropbox.com/s/xj9pbta1nmwzy3n/emotion_dataset_jira.zip?dl=0). 


# Please cite :)!

@inproceedings{Ortu2015,
abstract = {Issue tracking systems store valuable data for testing hypotheses concerning maintenance, building statistical prediction models and the social interactions of developers when interacting with peers. In particular, the Jira Issue Tracking System (ITS) is a proprietary tracking system that has gained a tremendous popularity in the last years and offers unique features like a project management system and the Jira agile kanban board. This paper presents a dataset extracted from the Jira ITS of four popular open source ecosystems (as well as the tools and infrastructure used for extraction), i.e., the Apache Software Foundation, Spring, JBoss and CodeHaus communities. Our dataset hosts more than 1K projects, containing more than 700K issue reports and more than 2 million issue comments. Using this data, we have been able to deeply study the communication process among developers, and how this aspect aspects the development process. For example, we found that comments posted by developers contain not only technical information, but also valuable information about sentiments and emotions. With this repository we would like to encourage further studies in these directions.},
author = {Ortu, Marco and Destefanis, Giuseppe and Murgia, Alessandro and Marchesi, Michele and Tonelli, Roberto and Adams, Bram},
booktitle = {Submitted to PROMISE '15},
keywords = {Affective Analysis,Issue Report,Mining software repository},
title = ,
year = {2015}
}
