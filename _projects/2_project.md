---
layout: page
title: Seismic damage prediction for residential buildings in Mexico City
description: Applied data science and machine learning to building damage data collected following the 2017 Puebla earthquake
img: assets/img/Mexico_paper-Fig6.jpg
importance: 2
category: seismic
---

On 19 September 2017, a magnitude Mw 7.1 earthquake struck the central part of Mexico. It originated in the Puebla region and affected the Puebla, Morelos and Mexico City area. In the urban area, 77 buildings partially or totally collapsed, and 8,000 buildings experienced different levels of damage.

I had the chance to be part of the New Zealand team that was sent for a week to Mexico City at the end of October 2017. I extended my stay to spend a few more weeks on site. I collaborated with the research team led by Prof. Alonso Gómez-Bernal and Prof. Hugon Juárez-Garcia. Together with their students, we focus on the collection of residential building damage data for the neighborhoods of la Roma and la Condesa. The damage data collection work continued and collaboration continued after my come back to New Zealand. Overall, damaged information on 340 buildings were collected.

This damage information of residential building was used for the development of a seismic damage prediction model using machine learning (ML). The building damage data was enriched with information about the seismic intensity. Once merged, the data was preprocessed to be able to be used by machine learning. Four algorithms were trialled: logistic regression, support vector machine (SVM), decision tree, and random forest. Random forest was retained for its prediction performance and for the insights that could be derived from the analysis of the feature importance.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Mexico_paper-Fig6.jpg" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Mexico_paper-Fig11.jpg" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    (a) Map of the assessed buildings in the Roma and Condesa neighborhoods, (b) Process to obtain the seismic demand for each building
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Mexico_paper-Fig9.jpg" title="Buildings assessed by the UAM team in the Roma and Condesa neighborhoods." class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Mexico_paper-Fig18.jpg" title="example image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    (a) Development of the machine learning model, (b) SHAP Feature importance of the random forest model
</div>


**Related publications**

Roeslin, S., Ma, Q., Juárez-Garcia, H., Gómez-Bernal, A., Wicker, J., & Wotherspoon, L. (2020). A machine learning damage prediction model for the 2017 Puebla-Morelos, Mexico, earthquake. Earthquake Spectra, 36(2_suppl).
<a href='https://doi.org/10.1177/8755293020936714'>https://doi.org/10.1177/8755293020936714</a>
