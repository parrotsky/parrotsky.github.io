---
# === Required fields  ===
# Your name 
name: "Xiaotian Guo"
# Your profile picture
imgname: 
  name: "img/main.jpg"
  alt: "Picture of me"
  type: image/jpeg
# More sources can be added (optional) using 
# imgOther:
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
# ...
# A title (job title or "Researcher", "PhD student", etc.)
personal_title: "Ph.D. in \   
     Parallel Computing Systems for Distributed AI Inference"
affiliation: University of Amsterdam, Leiden University
# An address (you can list multiple)
address: 
  - 
    name: University of Amsterdam,   Leiden University
    # email: gxtzhuxi@gmail.com
    # street:  
    # postal_code: "000000"
    # locality: Earth


# === Optional fields ===
# Add an email with a mailto: hyperlink
# email: aaaa@example.com
# Add an email "image" for spam protection. With light and dark mode
# emailImg: 
#   dark: /img/dark_email.png
#   light: /img/light_email.png

# List your publications. The required fields are pdf, title, and image 
# (which should be the image path). The other fields are optional.
publications:
  - 
    authors:
        - name: Xiaotian Guo
          me: true
        - name: Quan Jiang
        - name: Yixian Shen,  
        - name: Andy Pimentel,  
        - name: Todor Stefanov 
    title: "EASTER: learning to split transformers robustly at the Edge"
    # Will write "In ${journal}, ${date}"
    date: 2024
    journalconference: IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)
    image: img/splittransformer.svg
    # A bibtex (or any other format) citation that people can copy directly from the website.
    citation: "@article{guo2024easter,\n
  title={EASTER: learning to split transformers robustly at the Edge},\n
  author={Guo, Xiaotian and others},\n
  journal={IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)},\n
  year={2024},\n
  publisher={IEEE}\n
  }"
    pdf: https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=43
    # A list of link that will appear as badges at the bottom of the publication.
    links:
      -
        name: Main URL
        url: "https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=43"
      -
        name: ResearchGate
        url: "https://www.researchgate.net/profile/Xiaotian-Guo-7"
    # A description for the paper.
    description: Prevalent large transformer models present significant computational challenges for resource-constrained devices at the Edge. In this paper, we introduce a novel methodology, called EASTER, designed to learn robust distribution strategies for transformer models against device failures that consider the trade-off between robustness (i.e., maintaining model functionality against failures) and resource utilization (considering memory usage and computations).  We evaluate EASTER with three representative transformers ViT, GPT-2, and Vicuna under device failures. Our results demonstrate EASTER's efficiency in memory usage, and possible end-to-end latency improvement for inference across multiple edge devices while preserving model accuracy as much as possible under device failures. 
  - 
    authors:
        - name: Xiaotian Guo
          me: true
        - name: Quan Jiang 
        - name: Andy Pimentel, 
        - name: Todor Stefanov
    title: "RobustDiCE: Robust and Distributed CNN Inference at the Edge"
    # Will write "In ${journal}, ${date}"
    date: 2023
    journalconference: Proceedings of the 29th Asia and South Pacific Design Automation Conference (ASPDAC '24)
    image: img/robustdice.svg
    # A bibtex (or any other format) citation that people can copy directly from the website.
    citation: "@INPROCEEDINGS{guo2023robustdice,\n
        author={Guo, Xiaotian and others},\n
        booktitle={2024 29th ASP-DAC}, \n
        title={RobustDiCE: Robust and Distributed CNN Inference at the Edge}, \n
        year={2024},\n
        pages={26-31},\n
        doi={10.1109/ASP-DAC58780.2024.10473970}\n
        publisher={ACM}\n
        }"
    pdf: https://dl.acm.org/doi/10.1109/ASP-DAC58780.2024.10473970
    # A list of link that will appear as badges at the bottom of the publication.
    links:
      -
        name: Main URL
        url: "https://dl.acm.org/doi/10.1109/ASP-DAC58780.2024.10473970"
      -
        name: ResearchGate
        url: "https://www.researchgate.net/publication/379276607_RobustDiCE_Robust_and_Distributed_CNN_Inference_at_the_Edge"
    # A description for the paper.
    description: In this paper, we present a novel partitioning method, called RobustDiCE, for robust distribution and inference of CNN models over multiple edge devices. Our method can tolerate intermittent and permanent device failures in a distributed system at the Edge, offering a tunable trade-off between robustness (i.e., retaining model accuracy after failures) and resource utilization. We evaluate RobustDiCE using the ImageNet-1K dataset on several representative CNN models under various device failure scenarios and compare it with several state-of-the-art partitioning methods as well as an optimal robustness approach (i.e., full neuron replication).  In addition, we demonstrate RobustDiCE's advantages in terms of memory usage and energy consumption per device, and system throughput for various system set-ups with different device counts.
  - 
    authors:
        - name: Xiaotian Guo
          me: true
        - name: Andy Pimentel 
        - name: Todor Stefanov
    title: "Automated Exploration and Implementation of Distributed CNN Inference at the Edge"
    # Will write "In ${journal}, ${date}"
    date: 2023
    journalconference:  IEEE Internet of Things Journal
    image: img/designflow.svg
    # A bibtex (or any other format) citation that people can copy directly from the website.
    citation: "@ARTICLE{guo2021autodice,\n
    author={Guo, Xiaotian and others},\n
    journal={IEEE Internet of Things Journal}, \n
    title={Automated Exploration and Implementation of Distributed CNN Inference at the Edge}, \n
    year={2023},\n
    volume={10},\n
    number={7},\n
    pages={5843-5858},\n
    doi={10.1109/JIOT.2023.3237572}\n
    }"
    pdf: https://ieeexplore.ieee.org/document/10018439
    # A list of link that will appear as badges at the bottom of the publication.
    links:
      -
        name: Main URL
        url: "https://ieeexplore.ieee.org/document/10018439"
      -
        name: ResearchGate
        url: "https://www.researchgate.net/publication/367232620_Automated_Exploration_and_Implementation_of_Distributed_CNN_Inference_at_the_Edge"
    # A description for the paper.
    description: In this paper, we propose a novel framework that automates the splitting of a CNN model into a set of sub-models as well as the code generation needed for the distributed and collaborative execution of these sub-models on multiple, possibly heterogeneous, edge devices, while supporting the exploitation of parallelism among and within the edge devices. In addition, since the number of different CNN mapping possibilities on multiple edge devices is vast, our framework also features a multi-stage and hierarchical Design Space Exploration methodology to efficiently search for (near-)optimal distributed CNN inference implementations. Our experimental results demonstrate that our work allows for rapidly finding and realizing distributed CNN inference implementations with reduced energy consumption and memory usage per edge device, and under certain conditions, with improved system throughput as well.
  - 
    authors:
        - name: Xiaotian Guo
          me: true
        - name: Andy Pimentel 
        - name: Todor Stefanov
    title: "Hierarchical design space exploration for distributed CNN inference at the edge"
    # Will write "In ${journal}, ${date}"
    date: 2022
    journalconference: Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML PKDD 2022)
    image: img/hieworkflow.svg
    # A bibtex (or any other format) citation that people can copy directly from the website.
    citation: "@inproceedings{guo2022hierarchical,\n
  title={Hierarchical design space exploration for distributed CNN inference at the edge},\n
  author={Guo, Xiaotian and others},\n
  booktitle={3rd ITEM},\n
  pages={545--556},\n
  year={2022},\n
  organization={Springer},\n
  doi={10.1007/978-3-031-23618-1_36}\n
  }"
    pdf: https://link.springer.com/chapter/10.1007/978-3-031-23618-1_36
    # A list of link that will appear as badges at the bottom of the publication.
    links:
      -
        name: Main URL
        url: "https://link.springer.com/chapter/10.1007/978-3-031-23618-1_36"
      -
        name: ResearchGate
        url: "https://www.researchgate.net/publication/367536886_Hierarchical_Design_Space_Exploration_for_Distributed_CNN_Inference_at_the_Edge"
    # A description for the paper.
    description: In this paper, we present an efficient DSE methodology to find (near-)optimal CNN mappings for distributed inference at the edge. To deal with the vast design space of different CNN mappings, we accelerate the searching process by proposing and utilizing a multi-stage hierarchical DSE approach together with a tailored Genetic Algorithm as the underlying search engine. 

---

<!-- # Bio

My name is **Xiaotian Guo** (You can call me Sky in English). I am currently a Guest Researcher at University of Amsterdam, working closely with Prof. Andy Pimentel and Dr. Todor Stefanov. I finished my Ph.D. at Amsterdam Parallel Computing Systems Lab (PCS), University of Amsterdam. Thanks to my great Ph.D. supervisors,  Prof. Andy Pimentel and Dr. Todor Stefanov, for supporting me in finishing this project. 

Moreover, my research focuses on the distributed inference of deep learning models at the Edge. The principal goal of my Ph.D. project is to achieve **fast**, **safe**, **robust** and **efficient** execution of deep learning models over edge devices. I have published 1 TCAD jouranl paper, 1 IoT journal papers, 1 ASP-DAC Conference paper, 1 ECML-PKDD workshop paper. My PhD thesis " Distributed DNN inference at the Edge " is available in the link, together with the defense video in the link. 

More interesting work is ongoing and please follow my updates though [Googlescholar]([‪Xiaotian Guo‬ - ‪Google Scholar‬](https://scholar.google.com/citations?user=phnm-TwAAAAJ)) (Only selected publications appear in the googlescholar). For any guys who want to achieve scientific collaboration in publishing interesting papers, feel free to contact me😎. -->
