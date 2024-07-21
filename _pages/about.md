---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am currently a postdoctoral fellow at [the School of Computer Science and Engineering](https://cse.seu.edu.cn) at [Southeast University](https://www.seu.edu.cn). I earned both my PhD and master's degrees in Software Engineering from Southeast University. My undergraduate degree in Internet of Things Engineering was obtained from [Northeastern University](https://www.neu.edu.cn).

I am broadly interested in developing artificial intelligence, specifically focusing on integrating structured or semi-structured knowledge into foundation models like large language models (LLMs) to enhance their performance in question answering and other more complex tasks.
I am also concerned with the continual learning capability of the foundation model, to adapt and evolve over time. This requires mechanisms to update its knowledge base in response to new knowledge, trends, and changes in the environment it operates within.


Publications
======
([Google Scholar](https://scholar.google.com/citations?user=8ZjIHyEAAAAJ&hl=zh-CN&oi=ao))

* [2024] **DoG-Instruct: Towards Premium Instruction-Tuning Data via Text-Grounded Instruction Wrapping**

    **Yongrui Chen**, Haiyun Jiang, Xinting Huang, Shuming Shi, Guilin Qi.
    In the Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL'24) [[paper](https://aclanthology.org/2024.naacl-long.230.pdf)][[code](https://github.com/Bahuia/Dog-Instruct)]

* [2023] **Parameterizing Context: Unleashing the Power of Parameter-Efficient Fine-Tuning and In-Context Tuning for Continual Table Semantic Parsing**

    **Yongrui Chen*** , Shenyu Zhang*, Guilin Qi, Xinnan Guo.
    In the Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS'23) [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/398b00a05b847ac65eb98c8e5e865fe8-Paper-Conference.pdf)][[code](https://github.com/Bahuia/C3)] (*: Equal Contribution)

* [2023] **Learn from yesterday: A semi-supervised continual learning method for supervision-limited text-to-sql task streams**

    **Yongrui Chen**, Xinnan Guo, Tongtong Wu, Guilin Qi, Yang Li, Yang Dong.
    In Proceedings of the AAAI Conference on Artificial Intelligence (AAAI'23) [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/26492)][[code](https://github.com/Bahuia/SSCL-Text2SQL)]

* [2023] **Outlining and Filling: Hierarchical Query Graph Generation for Answering Complex Questions Over Knowledge Graphs**

    **Yongrui Chen**, Huiying Li, Guilin Qi, Tianxing Wu, Tenggou Wang.
    In IEEE Transactions on Knowledge and Data Engineering (TKDE) [[paper](https://ieeexplore.ieee.org/abstract/document/9895199)][[code](https://github.com/Bahuia/HGNet)]

* [2021] **Leveraging table content for zero-shot text-to-sql with meta-learning**

    **Yongrui Chen**, Xinnan Guo, Chaojie Wang, Jian Qiu, Guilin Qi, Meng Wang, Huiying Li.
    In Proceedings of the AAAI Conference on Artificial Intelligence (AAAI'21) [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16519)][[code](https://github.com/Bahuia/HGNet)]

* [2020] **Formal query building with query structure prediction for complex question answering over knowledge base**

    **Yongrui Chen**, Huiying Li, Yuncheng Hua, Guilin Qi.
    In Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence. (IJCAI'20) [[paper](https://www.ijcai.org/proceedings/2020/0519.pdf)][[code](https://github.com/Bahuia/AQGNet)]


Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right.
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

