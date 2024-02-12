Soil Physics
==================

Pedotransfer functions
-----------
Guber et al. (2006)
++++++++++++++++++
Guber, A. K., Pachepsky, Y. A., Van Genuchten, M. T., Rawls, W. J., Simunek, J., Jacques, D., ... & Cady, R. E. (2006). Field-scale water flow simulations using ensembles of pedotransfer functions for soil water retention. Vadose Zone Journal, 5(1), 234-247. https://doi.org/10.2136/vzj2005.0111.

The research focuses on the use of pedotransfer functions (PTFs) to estimate soil hydraulic properties for simulating soil water flow, particularly for large-scale projects or pilot studies. The study emphasizes the challenges of applying PTFs outside their development dataset, highlighting the variability in model performance across different regions. To address these challenges, an ensemble approach of 22 published PTFs was utilized, leveraging their collective predictive power to improve the accuracy of soil water regime simulations. The study was conducted on a layered loamy soil in Belgium, incorporating soil water content, pressure head measurements, and water flux data from a specifically designed experimental setup.

Key findings are:

- The ensemble of PTFs produced significantly more accurate soil water content simulations compared to using laboratory-measured water retention data alone, with average errors being two times smaller for the ensemble approach.

- The research demonstrated that the ensemble method provided a better approximation of field water retention, suggesting its potential as a reliable source for estimating soil hydraulic properties.

- Despite the inherent uncertainties in using PTFs developed from different datasets and regions, the ensemble approach mitigated these issues, offering a promising methodology for improving the simulation of soil water dynamics.

- The study also underlined the importance of considering the variability and uncertainty associated with both laboratory-measured and PTF-estimated data in soil hydraulic property simulations.

Important results are:

- The use of an ensemble of 22 published PTFs significantly reduced the average simulation errors when compared to using laboratory-measured data, highlighting the effectiveness of the ensemble approach in soil water content simulations.

- The ensemble approach's ability to closely approximate field water retention compared to laboratory data, indicating its potential reliability for estimating soil hydraulic properties.

- The acknowledgment of variability and uncertainty in PTF-based estimations and the strategies employed to address these challenges in the context of soil water flow simulations.

van Looy et al. (2017)
++++++++++++++++++
Van Looy, K., Bouma, J., Herbst, M., Koestel, J., Minasny, B., Mishra, U., ... & Vereecken, H. (2017). Pedotransfer functions in Earth system science: Challenges and perspectives. Reviews of Geophysics, 55(4), 1199-1256. https://doi.org/10.1002/2017RG000581.

The research provides a review of pedotransfer functions (PTFs), which are rules or models used to estimate soil properties based on more easily measured or known soil characteristics. These PTFs are essential for modeling and understanding soil processes, especially in the context of Earth system sciences, where accurate parameterization of soil processes is crucial for predicting the dynamics of land surface under changing climate and land use.

Key points are:

- The importance of PTFs in estimating soil properties that are difficult, expensive, or impossible to measure directly. This is vital for modeling soil processes accurately, which is crucial for understanding and predicting changes in the Earth system, including climate change and land use impacts.

- The evolution of PTFs from simple empirical relationships to complex models incorporating a wide range of soil properties. The development of new PTFs, driven by advancements in soil science and technology, allows for better parameterization of soil processes in Earth system models.

- The need for methodological advancements in PTF development, emphasizing the importance of suitable extrapolation and upscaling techniques. These advancements ensure that PTFs accurately represent the spatial heterogeneity of soils and can be used confidently for modeling purposes at various scales.

- Challenges in parameterizing soil processes, such as soil erosivity and the impacts of land use change, which require further research and development of PTFs. Addressing these challenges is crucial for improving the accuracy and reliability of Earth system models.

- The role of novel sensing techniques and data sources, such as Global Soil Map products, in enhancing the development and application of PTFs. These technologies provide high-resolution soil information, enabling the development of more accurate and spatially explicit PTFs.

- The application of PTFs across a wide range of disciplines within Earth system science, highlighting their significance in improving land surface models and understanding the impacts of climate and land use changes on soil processes.

- The quality of PTFs is quantitatively assessed using metrics such as root-mean-square errors (RMSEs), mean errors (MEs), and the coefficient of determination (R^2). RMSE quantifies the average variance between estimated and measured values, ME identifies systematic biases, and R^2 indicates the proportion of variance explained by the model. Absolute mean errors and relative mean errors (RME) or unbiased RMSE (URMSE) are also used to separate systematic from random errors.

- The performance of PTFs varies based on the data set (local-regional, soil types) and the range of input variables used. This variability underscores the importance of context in evaluating PTF methodology, as different techniques may yield varying conclusions on the best PTF development approach.

- When choosing PTF development techniques, it's crucial to consider not only model performance metrics but also other attributes of modeling techniques, such as interpretability, variable selection capability, handling of mixed data types, and computational efficiency. Despite often small and inconsistent differences in reported performance metrics, these additional characteristics can significantly impact the utility of PTFs in application.

- Addressing challenges such as extrapolation, scaling, and integration is essential for enhancing PTF utility in Earth system modeling. This includes ensuring that PTFs are representative of the application domain, understanding the impact of spatial scale on PTF performance, and integrating PTFs with other models or data sets to improve predictions at various scales.

- Axis 1 (Identification): Leveraging improved process understanding and relationships to enhance parameter estimations, especially incorporating biogeochemical and biotic processes into ESMs. This includes evaluating and potentially revising default model parameters based on new insights and high-resolution soil data.

- Axis 2 (Validation): Validating developed PTFs for large-scale applications involves addressing methodological challenges in extrapolation and upscaling, as well as utilizing newly derived global soil hydraulic functions.

- Axis 3 (Integration): Integrating comprehensive knowledge into ESMs by developing suites of PTFs for complex biogeochemical processes. Coupled model parameterizations can improve simulations of soil processes, contributing to better predictions of ecosystem services and responses to environmental changes.

- Emerging techniques like soil spectroscopy and advanced remote sensing platforms offer new opportunities for PTF development and model validation. These methods can provide detailed soil property data essential for constructing and validating PTFs.

- Addressing uncertainty in PTF estimates and model predictions is crucial. Future research should focus on quantifying and mitigating uncertainties associated with PTFs, including those arising from measurement variability, model assumptions, and spatial aggregation of soil properties.


Parameter estimation
----------------------
Hodnett and Tomasella (2002)
++++++++++++++++++
Hodnett, M. G., & Tomasella, J. (2002). Marked differences between van Genuchten soil water-retention parameters for temperate and tropical soils: a new water-retention pedo-transfer functions developed for tropical soils. Geoderma, 108(3-4), 155-180. https://doi.org/10.1016/S0016-7061(02)00105-2.

This research focused on deriving Pedo-Transfer Functions (PTFs) for water retention in tropical soils, utilizing the IGBP-DIS soil database, which included data from 771 suitable horizons. The study aimed to fill the gap in understanding and predicting the hydraulic properties of tropical soils, which are often distinct from temperate region soils due to differences in texture, structure, and mineralogy.

Core methods are:

- Data Source: IGBP-DIS soil database with emphasis on tropical soils.
- Key Parameters: The van Genuchten equation parameters (θs, θr, α, n) were derived for tropical soils and compared with temperate soil data sets.
- Multiple regression techniques were used to develop both class and continuous PTFs, incorporating variables like soil texture, bulk density, and organic carbon content.

Major findings are:

- Tropical soils showed a higher proportion of clays and significantly lower bulk densities across various textural classes when compared to temperate soils. This influences the water retention characteristics, resulting in higher saturated water content (θs) and residual water content (θr) for tropical soils.

- The α parameter, indicating the inverse of the air entry value, was generally higher for tropical soils, suggesting larger pore spaces and more structured soils, particularly in kaolinitic soils compared to montmorillonitic soils. The parameter n, which determines the steepness of the water-release curve, was also found to be significantly different when comparing tropical to temperate soils.

- The study highlighted the importance of including mineralogy in PTFs, as it significantly affects the water retention properties, especially in tropical soils where kaolinitic and montmorillonitic clays behave differently.

New PTF summary:

- Class vs. Continuous PTFs: A continuous PTF was developed and found to predict water-retention curves more reliably than class PTFs for tropical soils. However, it was noted to be less reliable for soils with very low density, like Andosols.
- Limitations: The research acknowledged the challenge in predicting the hydraulic properties of soils with extreme properties (either very high or very low α values) and the lack of hydraulic conductivity data as a significant gap for modeling water movement in tropical soils.

Schaap et al. (2001)
++++++++++++++++++
Schaap, M. G., Leij, F. J., & Van Genuchten, M. T. (2001). Rosetta: A computer program for estimating soil hydraulic parameters with hierarchical pedotransfer functions. Journal of hydrology, 251(3-4), 163-176. https://doi.org/10.1016/S0022-1694(01)00466-8.

The research introduces "Rosetta," a computer program designed to estimate soil hydraulic properties—water retention, saturated hydraulic conductivity (Ks), and unsaturated hydraulic conductivity—using pedotransfer functions (PTFs). Given the practical and financial limitations often associated with measuring these properties directly, Rosetta offers a valuable tool for hydrological studies involving water and solute transport.

Key Features are:

Rosetta employs a set of five hierarchical PTFs, allowing for the estimation of soil hydraulic parameters with varying levels of input data—from basic textural information to more comprehensive data including texture, bulk density, and water retention points. The program utilizes neural network analyses combined with the bootstrap method, enabling it to provide uncertainty estimates for the predicted hydraulic parameters. This feature is crucial for assessing the reliability of the estimates in the absence of direct hydraulic data. Rosetta's performance was evaluated using coefficients of determination (R²) and root mean square errors (RMSEs), showing improved accuracy with the inclusion of more predictors. For water retention, RMSE values ranged from 0.078 to 0.044 cm³ cm⁻³, and for saturated conductivity, RMSE decreased from 0.739 to 0.647 in log10 units. Unsaturated conductivity RMSE values varied between 0.79 and 1.06, based on the nature of the retention parameters used (measured or estimated). Rosetta provides uncertainty estimates for its predictions, offering insights into model reliability. This feature is particularly useful for hydrologic modeling and decision-making when direct measurements are unavailable.

Implications of Rosetta are:

Rosetta's hierarchical approach and its ability to incorporate varying levels of detail make it adaptable to a wide range of situations. The program is particularly beneficial for large-scale hydrological studies where direct measurement of soil hydraulic properties is impractical. Compared to traditional PTFs, Rosetta offers more accurate estimates and the ability to gauge the reliability of these estimates through uncertainty analysis. With its graphical user interface, Rosetta is accessible to users who may not have extensive experience in hydrological modeling. Its database management features further facilitate the use and application of the PTFs. Rosetta can be downloaded for free from the US Salinity Laboratory website, making it widely accessible for research and practical applications in soil science and hydrology.

Zhang and Schaap (2017)
++++++++++++++++++++++++

This study presents Rosetta3, an enhanced version of the Rosetta pedotransfer function (PTF), originally known as Rosetta1 (Schaap et al., 2001). Rosetta3 advances the methodology by unifying the estimation of van Genuchten water retention parameters, saturated hydraulic conductivity (Ks), and their uncertainties into a single model framework. The improvements include the use of artificial neural network (ANN) analysis combined with an expanded bootstrap re-sampling method, utilizing one thousand replicas for calibration, compared to 60 or 100 in the original version. This approach allows for a detailed quantification of univariate and bivariate probability distributions of predicted parameters.

Key findings are:

Rosetta3 builds upon Rosetta1 by integrating water retention and Ks submodels, enhancing the estimation accuracy and reliability of soil hydraulic parameters. By incorporating the uncertainty of fitted van Genuchten parameters in the ANN calibration, Rosetta3 reduces bias in predicted parameters and provides a more detailed uncertainty analysis. The study found that estimated distributions of parameters are better described by heavy-tailed α-stable distributions rather than Gaussian distributions, especially for parameters with extreme silt and clay content. While the root mean square error (RMSE) for water content showed modest improvements, the RMSE for Ks increased slightly in the new models. However, the reduction in matric potential-dependent bias and the detailed characterization of uncertainty and distribution types are significant advancements. Rosetta3, along with Rosetta1, has been implemented in Python, making the models accessible as open-source code and ensuring platform independence. This facilitates integration into existing research or commercial software.

Summary of improvements is provided below:

Significant reduction in matric potential-dependent bias for estimated water contents, particularly for pressures higher than 32 cm. Modest reductions in RMSE for water content (about 5% to 15% improvement) compared to Rosetta1, with a slight increase in RMSE for Ks (0.9% to 3.3%). The discovery that estimated distributions are non-Gaussian and align more closely with α-stable distributions, particularly in textures poorly represented in the calibration database.

Carsel and Parrish (1988)
++++++++++++++++++++++++
Carsel, R. F., & Parrish, R. S. (1988). Developing joint probability distributions of soil water retention characteristics. Water resources research, 24(5), 755-769. https://doi.org/10.1029/WR024i005p00755.

This article provides a detailed overview of the methodology and findings related to assessing the soil properties and uncertainty in groundwater contamination due to chemical transport through the unsaturated zone. Groundwater contamination is influenced by soil characteristics, spatial variability, and meteorological conditions, which contribute to the uncertainty in predicting chemical movement and eventual contamination levels. The text highlights the use of Monte Carlo simulation methods to address this uncertainty, leveraging probability density functions of model input parameters and accounting for correlations among these parameters.

Core methods are:

- Monte Carlo simulations are employed to evaluate the uncertainty of solute transport. This approach utilizes randomly generated time series to produce frequency distributions, which help in assessing the probability of groundwater contamination levels. Monte Carlo simulations require a detailed understanding of probability distributions for hydraulic parameters that influence water and solute movement in soil.

- To address the lack of distributional and correlational information for hydraulic parameters, estimation methods are developed for essential parameters required by solute transport models. This enables the inference of associated probability distributions for model input parameters.

- The Johnson system is used to fit empirical distributions for hydraulic parameters, providing a variety of forms suitable for data fitting. This system allows for the transformation of variables to achieve normally distributed variables, which is advantageous for Monte Carlo simulations.

Important parameters are:

- Coefficient of Variation (CV) is used to represent the variability in soil hydraulic properties, with higher CVs indicating greater variability. This parameter is crucial for understanding the spatial variability in soil characteristics that can affect chemical transport.

- Probability Density Functions are developed for soil-saturated hydraulic conductivity and other hydraulic parameters, these functions are essential for characterizing the input parameters in solute transport models.

- The inclusion of correlations in a multivariate normal distribution model allows for a more accurate representation of the relative frequencies of variables under study, indicating that some combinations of values are more or less probable than others.

- The Johnson system's flexibility in fitting a variety of distribution forms makes it particularly useful for approximating many empirical distributions. The choice of transformation (lognormal, SB, or SU) depends on achieving the best fit to empirical data.

Major findings are:

- The study documents considerable variability in soil hydraulic properties, which significantly impacts the prediction of solute movement and groundwater contamination.

- For various soil textural classes, probability density functions were developed for soil-saturated hydraulic conductivity and other hydraulic parameters, incorporating correlations among variables to more accurately represent their joint distribution.

- Incorporating correlations among input variables in Monte Carlo simulations reduces uncertainty, as demonstrated by the reduction of uncertainty by one third when correlations are accommodated.

Wyatt et al. (2021)
++++++++++++++++++++++++
Wyatt, B. M., Ochsner, T. E., Brown, W. G., Diggins, D. C., Illston, B. G., & Fiebrich, C. A. (2021). MesoSoil v2. 0: An updated soil physical property database for the Oklahoma Mesonet. Vadose Zone Journal, 20(4), e20134. https://doi.org/10.1002/vzj2.20134.

This study presents the development and evaluation of an updated Oklahoma Mesonet soil physical property database, MesoSoil v2.0, which incorporates the Rosetta3 pedotransfer function for estimating soil water retention parameters. The updated database aims to improve soil moisture estimates by incorporating soil sampling data from additional locations and using an advanced version of the Rosetta model for better prediction accuracy.

- Rosetta3, an advanced hierarchical artificial neural network model, is utilized for estimating soil water retention parameters. This model unifies water retention and saturated hydraulic conductivity prediction models and is implemented in Python, offering advantages over the previous Rosetta1 model.

- Soil physical properties were measured at various depths across over 100 Oklahoma Mesonet station locations. The comprehensive Rosetta model (H5) was primarily used for data analysis, supplemented by H2 and H3 models when input data were missing.

- Linear interpolation was employed to estimate soil physical properties at the 10-cm depth for sites without measured data. This method showed good agreement with measured values, indicating its efficacy for filling data gaps.

- The study compared estimated soil water retention parameters and their effects on volumetric water content estimates between the Rosetta1 and Rosetta3 models. Significant changes were observed, particularly in the parameter α, related to the inverse of the air-entry potential, which decreased in value.

- Estimated Water Retention Parameters: The use of Rosetta3 led to statistically significant changes in estimated parameters. The most notable was a decrease in the α parameter, resulting in differences in volumetric water content estimates, especially during wet conditions.

- Accuracy of Volumetric Water Content Estimates: The mean absolute differences (MAD) in volumetric water content estimates between the two models averaged 0.02 cm³ cm⁻³ across all site-years, with the updated MesoSoil v2.0 database providing estimates closer to measured values.

- Improvement Over Previous Studies: Compared to the original Rosetta model, Rosetta3 and the updated database enhance the accuracy of soil moisture estimates, as evidenced by a better match with measured volumetric water content and a reduced MAD.

