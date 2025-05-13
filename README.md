# MetaBoost
### Enhancing Metabolic Syndrome Prediction with Hybrid Data Balancing and Counterfactuals
_Sanyam Paresh Shah, Abdullah Mamun, Shovito Barua Soumma, Hassan Ghasemzadeh_

Accepted at <span style="color: green;">The 47th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), July 14–17, 2025, Copenhagen, Denmark.</span>

MetaBoost is an explainable machine learning system for predicting Metabolic Syndrome (MetS).


Read the full paper here: https://arxiv.org/abs/2504.06987


Bibtex for citing the work:
```
@misc{shah2025enhancingmetabolicsyndromeprediction,
      title={Enhancing Metabolic Syndrome Prediction with Hybrid Data Balancing and Counterfactuals}, 
      author={Sanyam Paresh Shah and Abdullah Mamun and Shovito Barua Soumma and Hassan Ghasemzadeh},
      year={2025},
      eprint={2504.06987},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2504.06987}, 
}
```

### Method
The MetaBoost framework addresses the challenges of predicting Metabolic Syndrome (MetS) by leveraging advanced data balancing techniques and counterfactual analysis to optimize machine learning models.

MetaBoost uses a novel hybrid data balancing  approach that combines SMOTE, ADASYN, and CTGAN with weighted averaging and iterative weight tuning, achieving up to a 1.87% accuracy improvement. Multiple ML models (e.g., XGBoost, Random Forest, TabNet) were systematically evaluated. Furthermore, counterfactual analysis identifies critical feature-level changes—such as reductions in blood glucose and triglycerides—to transition individuals from high-risk to low-risk categories, providing actionable insights for clinical interventions.

### Dataset
The original dataset is available here: https://www.kaggle.com/datasets/antimoni/metabolic-syndrome

For more resources, please visit https://ghasemzadeh.com/publication/2025-sanyam-metaboost/

### Contact Information
For questions or concerns, please contact Abdullah Mamun (a.mamun@asu.edu) or Sanyam Paresh Shah (sshah174@asu.edu).
