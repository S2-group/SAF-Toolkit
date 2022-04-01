# SAF-Toolkit
# Sustainability Assessment Framework (SAF) Toolkit
This reporitory contains the material of SAF-Tooolkit, a set of instruments to design the network of sustainability-quality concerns at the software architecture level, and define and operationalize them.

The SAF-Toolkit was developed at the Vrije Universiteit Amsterdam. It entails the following instruments:
1. **Decision Map (DM)** visual notation (library to be used in the [Draw.io or Diagrams.net tool](https://www.diagrams.net)): diagram framing and illustrating the (software architecture) sustainability-relevant design- and quality concerns and their related dependencies;
2. **Checklist**: reflective questions to help defining the elements of a DM; this include the **Decision Graph**, which helps the classification of concerns in the sustainability dimensions and level of impact;
3. **Dependency Matrix'es (DMatrix) template**: helps completing and complementing the own DM for the most relevant sustainability dimensions; identifying missing sustainability-quality concerns; and identifying missing dependencies. It includes: (i) instructions for use and extension; DMatrix of dependencies between SQ concerns (ii) in the Technical-Social dimensions; (iii) in the Technical-Environmental dimensions; and (iv) in the Technical-Economic dimensions (version 2022-04);
4. **Sustainability-Quality (SQ) Model template**: for each SQ concern (aka attribute aka characteristic), it captures consolidated definitions and the metrics/KPIs to operationalize them. It includes: (i) the template to define the own SQ model; and (ii) the SQ Model (version 1.1 dated 2022-04) created from past projects and the ISO/IEC 25010-2011 standard.

# SAF Conceptual Model
The concepts managed by the SAF Toolkit are visualized below:

<p align="center">
<img src="./documentation/SAFmodel.jpeg" alt="Overview of the SAF conceptual model" width="900"/>
</p>

## How to cite SAF Toolkit

If SAF Toolkit is helping your research or practice, please credit our work by citing it as follows, thanks!

``` 
@MISC{SAF_Toolkit_2022,
  title={{The Sustainability Assessment Framework Toolkit: Instruments to help Sustainability-driven Software Architecture Design Decision Making}},
  author={Patricia Lago and Nelly Condori-Fernandez},
  month=apr,
  year={2022},
  url= {https://github.com/S2-group/SAF-Toolkit},
  organization={S2~Group}
}
```

## Publications
The material included in this repository is based on the following publications:

> Lago, P. (2019). Architecture design decision maps for software sustainability. In IEEE/ACM 41st International Conference on Software Engineering: Software Engineering in Society (ICSE-SEIS) (pp. 61-64). [8797634]. https://doi.org/10.1109/ICSE-SEIS.2019.00015

> Condori-Fernandez, N., & Lago, P. (2018). Characterizing the contribution of quality requirements to software sustainability. Journal of Systems and Software, 137, 289-305. https://doi.org/10.1016/j.jss.2017.12.005

> Condori-Fernandez, N., & Lago, P. (2019). Towards a software sustainability-quality model: Insights from a multi-case study. In M. Kolp, J. Vanderdonckt, M. Snoeck, & Y. Wautelet (Eds.), 13th International Conference on Research Challenges in Information Science (RCIS). IEEE Computer Society. https://doi.org/10.1109/RCIS.2019.8877084

> Condori Fernandez, O. N., & Lago, P. (2019). Using Participatory Technical-action-research to validate a Software Sustainability Model. In A. Wolff (Ed.), ICT4S 2019 - Proceedings of the 6th International Conference on ICT for Sustainability. Lappeenranta, Finland, June 10-14, 2019. CEUR-WS. http://ceur-ws.org/Vol-2382/ICT4S2019_paper_1.pdf

> Condori-Fernandez, N., Lago, P., Luaces, M. R., & Places, Á. S. (2020). An action research for improving the sustainability assessment framework instruments. Journal of Sustainability (Switzerland), 12(4). [1682]. https://doi.org/10.3390/su12041682

Directory Structure
---------------
This is the root directory of the repository. The directory is structured as follows:

    SAF Toolkit
     .
     |        
     |--- documentation/                    Files used for the README
     |                         
     |--- SAF Toolkit [2022-04]/            Current version of the SAF Toolkit, including instruments                              
     |
     |--- tutorials/                        Tutorials on how to use the SAF Toolkit
