# Predictive Modeling of FRESH 3D Bioprinting Process Parameters with Non-Neural Network-Based Algorithms

This work investigates the use of non-neural network-based machine learning algorithms to predict optimal process parameters for Freeform Reversible Embedding of Suspended Hydrogels (FRESH) 3D bioprinting. These .ipynb files provide 

## Description

These .ipynb files provide an algorithm for OLS, LASSO, Random Forest Regressor, XGBoost Regressor, and Gaussian Process Regression for the collagen and alginate 3D print dataset. They are used to develop a predictive linear and nonlinear regression model with selected variables (x or h variables) and produce evaluation metrics with parity plots or uncertainty envelope plots (if applicable).

## Dataset
All files require a .xlsx raw dataset that contains x variables or h variables and associated line (Y1) and corner (Y3) print scores. The datasets containing the print scores of collagen and alginate FRESH prints were obtained from the authors of Hierarchical Machine Learning for High-Fidelity 3D Printed Biopolymers (https://pubs.acs.org/doi/10.1021/acsbiomaterials.0c00755?goto=supporting-info).

## Included Files: Required .xlsx Files
- xvar_regression.ipynb: Col_CornerScore_rawdata.xlsx, Col_LineScore_rawdata.xlsx 
- xvar_ensemble.ipynb: Collagen_rawdata.xlsx
- hvar_collagen_regression.ipynb: Collagen_middlelayers.xlsx
- hvar_alginate_regression.ipynb: Alginate_middlelayers.xlsx
- hvar_collagen_ensemble.ipynb: Collagen_middlelayers.xlsx
- hvar_alginate_ensemble.ipynb: Alginate_middlelayers.xlsx
- hvar_GPR_RBF.ipynb: Collagen_middlelayers.xlsx
- hvar_GPR_Matern.ipynb: Collagen_middlelayers.xlsx

### Dependencies

-  Describe any prerequisites, libraries, OS version, etc., needed before installing program.
-  ex. Windows 10

### Installing

- How/where to download your program
- Any modifications needed to be made to files/folders

### Executing program

- How to run the program
- Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

-  0.2
    - Various bug fixes and optimizations
    - See [commit change]() or See [release history]()
- 0.1
    - Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
