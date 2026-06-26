# Awesome PPT Generation

A curated list of papers, datasets, benchmarks, tools, and systems for **PPT generation**, **presentation generation**, **document-to-slides generation**, **LLM-based slide generation**, and **visual document generation**.

This repository focuses on research and systems related to automatically generating slides, presentations, posters, and other structured visual documents from documents, scientific papers, user instructions, or multimodal content.

## Contents

* [Papers](#papers)

  * [Document-to-Slides Generation](#document-to-slides-generation)
  * [LLM-based Presentation Generation](#llm-based-presentation-generation)
  * [Agentic and Multi-Agent Presentation Generation](#agentic-and-multi-agent-presentation-generation)
  * [Template-aware and Knowledge-centric Generation](#template-aware-and-knowledge-centric-generation)
  * [Poster and Visual Document Generation](#poster-and-visual-document-generation)
  * [Slide Understanding and Reverse Tasks](#slide-understanding-and-reverse-tasks)
* [Datasets and Benchmarks](#datasets-and-benchmarks)
* [Related Topics](#related-topics)
* [Contributing](#contributing)
* [License](#license)

## Papers

### Document-to-Slides Generation

* **DOC2PPT: Automatic Presentation Slides Generation from Scientific Documents**
  Fu, T.-J., Wang, W. Y., McDuff, D., & Song, Y. 2022.
  [[Paper]](https://doi.org/10.48550/arXiv.2101.11796)
  A representative work on generating presentation slides from scientific documents.

* **Presentations are not always linear! GNN meets LLM for Document-to-Presentation Transformation with Attribution**
  Maheshwari, H., Bandyopadhyay, S., Garimella, A., & Natarajan, A. 2024.
  [[Paper]](https://doi.org/10.48550/arXiv.2405.13095)
  Studies document-to-presentation transformation with graph-based modeling, LLMs, and attribution.

* **Automatic Summarization for the Generation of Slides**
  Costa, M. J. S. 2022.
  [[Thesis]](https://www.pqdtcn.com/thesisDetails/2D7AB181F0CEED8B2408A27D2E8749DD)
  Explores automatic summarization methods for slide generation.

### LLM-based Presentation Generation

* **Enhancing Presentation Slide Generation by LLMs with a Multi-Staged End-to-End Approach**
  Bandyopadhyay, S., Maheshwari, H., Natarajan, A., & Saxena, A. 2024.
  [[Paper]](https://doi.org/10.48550/arXiv.2406.06556)
  Proposes a multi-stage end-to-end approach for LLM-based presentation slide generation.

* **PPTAgent: Generating and Evaluating Presentations Beyond Text-to-Slides**
  Zheng, H., Guan, X., Kong, H., Zheng, J., Zhou, W., Lin, H., Lu, Y., He, B., Han, X., & Sun, L. 2025.
  [[Paper]](https://doi.org/10.48550/arXiv.2501.03936)
  Introduces an agent-based framework for generating and evaluating presentations beyond simple text-to-slides generation.

### Agentic and Multi-Agent Presentation Generation

* **PreGenie: An Agentic Framework for High-quality Visual Presentation Generation**
  Xu, X., Xu, X., Chen, S., Chen, H., Zhang, F., & Chen, Y.-C. 2025.
  [[Paper]](https://doi.org/10.48550/arXiv.2505.21660)
  Presents an agentic framework for high-quality visual presentation generation.

* **Auto-Slides: An Interactive Multi-Agent System for Creating and Customizing Research Presentations**
  Yang, Y., Jiang, W., Wang, Y., Wang, Y., & Zhang, C. 2025.
  [[Paper]](https://doi.org/10.48550/arXiv.2509.11062)
  Focuses on interactive multi-agent systems for creating and customizing research presentations.

### Template-aware and Knowledge-centric Generation

* **Knowledge-Centric Templatic Views of Documents**
  Cachola, I., Cucerzan, S., Herring, A., Mijovic, V., Oveson, E., & Jauhar, S. K. 2024.
  [[Paper]](http://dx.doi.org/10.48550/arXiv.2401.06945)
  Studies knowledge-centric templatic views of documents, which is related to structured document representation and template-based generation.

### Poster and Visual Document Generation

* **Paper2Poster: Towards Multimodal Poster Automation from Scientific Papers**
  Pang, W., Lin, K. Q., Jian, X., He, X., & Torr, P. 2025.
  [[Paper]](https://doi.org/10.48550/arXiv.2505.21497)
  Explores multimodal poster generation from scientific papers, closely related to visual document generation.

### Slide Understanding and Reverse Tasks

* **Slide2Text: Leveraging LLMs for Personalized Textbook Generation from PowerPoint Presentations**
  Zhou, Y. 2025.
  [[Paper]](https://doi.org/10.48550/arXiv.2503.17710)
  Studies the reverse direction of slide generation by converting PowerPoint presentations into personalized textbook-style text.

## Datasets and Benchmarks

* **DOC2PPT**
  A dataset for automatic presentation slide generation from scientific documents.
  Related paper: [DOC2PPT: Automatic Presentation Slides Generation from Scientific Documents](https://doi.org/10.48550/arXiv.2101.11796)

* **PPTEval**
  An evaluation setting for presentation generation and presentation quality assessment.
  Related paper: [PPTAgent: Generating and Evaluating Presentations Beyond Text-to-Slides](https://doi.org/10.48550/arXiv.2501.03936)

## Related Topics

* Document-to-slides generation
* Paper-to-slides generation
* LLM-based presentation generation
* Multi-agent presentation generation
* Template-aware slide generation
* Editable PowerPoint generation
* Slide layout generation
* Visual document generation
* Scientific poster generation
* Presentation evaluation
* Slide understanding

## Contributing

Contributions are welcome. Please feel free to submit pull requests to add papers, datasets, benchmarks, tools, systems, or related resources.

Suggested entry format:

```markdown
- **Paper Title**  
  Authors. Year.  
  [[Paper]]() [[Code]]() [[Project]]()  
  A short description of the main contribution.
```

Please make sure that the submitted resource is directly related to PPT generation, presentation generation, document-to-slides generation, slide layout generation, or visual document generation.

## License

This repository is released under the MIT License.
