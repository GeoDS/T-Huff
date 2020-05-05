# Calibrating the dynamic Huff model for business analysis using location big data
### Code and Data
`./code/` contains two versions of source code: one in Jupyter Notebook and the other in plain Python. 

`./data/` contains the data file to run the traditional and dynamic Huff models.

Reference: Liang, Y., Gao, S., Cai, Y., Foutz, N. Z., & Wu, L. (2020). Calibrating the dynamic Huff model for business analysis using location big data. Transactions in GIS. 24(3), 1-23. DOI: 10.1111/tgis.12624. 
arXiv preprint available at https://arxiv.org/abs/2003.10857.

### Abstract 
The Huff model has been widely used in location-based business analysis for delineating a trading area containing potential customers to a store. Calibrating the Huff model and its extensions requires empirical location visit data. Many studies rely on labor-intensive surveys. With the increasing availability of mobile devices, users in location-based platforms share rich multimedia information about their locations in a fine spatiotemporal resolution, which offers opportunities for business intelligence. In this research, we present a time-aware dynamic Huff model (T-Huff) for location-based market share analysis and calibrate this model using large-scale store visit patterns based on mobile phone location data across ten most populated U.S. cities. By comparing the hourly visit patterns of two types of stores, we demonstrate that the calibrated T-Huff model is more accurate than the original Huff model in predicting the market share of different types of business (e.g., supermarkets vs. department stores) over time. We also identify the regional variability where people in large metropolitan areas with a well-developed transit system show less sensitivity to long-distance visits. In addition, several socioeconomic and demographic factors (e.g., median household income) that potentially affect people's visit decisions are examined and summarized.

### More POI visit data: SafeGraph (https://shop.safegraph.com/)

### Considering the spatial interaction from different neighborhoods and temporal visit patterns

<img src="https://geods.geography.wisc.edu/wp-content/uploads/2020/05/map_arc_wholefoods.png"
     alt="Spatial Visit Patterns"
     style="float: left; margin-right: 10px;" width="600"  />
     
<img src="https://geods.geography.wisc.edu/wp-content/uploads/2020/04/tgis12624_HourlyPlot.png"
     alt="Preiction vs. Actual"
     style="float: left; margin-right: 10px;" width="600"  />

### Using Huff models for the store visit probability predictions and constructing market share areas
<img src="https://geods.geography.wisc.edu/wp-content/uploads/2020/04/tgis12624_prediction.jpg"
     alt="Preiction vs. Actual"
     style="float: left; margin-right: 10px;" width="600" />

### Reference
```
@article{liang2020calibrating,
  title={Calibrating the dynamic Huff model for business analysis using location big data},
  author={Liang, Yunlei and Gao, Song and Cai, Yuxin and Foutz, Natasha Zhang and Wu, Lei},
  url={arXiv preprint arXiv:2003.10857},
  journal={Transactions in GIS},
  year={2020}
  volume={24},
  number={3},
  pages={1--23},
  publisher={Wiley Online Library}
}
```
