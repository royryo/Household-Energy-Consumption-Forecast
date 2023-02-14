# Household Energy Load Forecast

## What is this project? 
Tokyo is facing an energy crisis with an increasing pressure to shift away from oil and fossil fuel. We propose a program that citizens can calculate and predict their energy consumption to contribute to reducing energy demands at its highest peaks. The forecast model uses open data from the [Tokyo Metropolitan Government](https://catalog.data.metro.tokyo.lg.jp/dataset). The project is on halt because of personal circumstances of the participating members. 

## The statistical model 
The program is based on the SVR model from a paper written by [Shen et. al](https://www.sciencedirect.com/science/article/pii/S1876610217359520?fr=RR-2&ref=pdf_download&rr=737df4bc893d80fb), and predicts with: 

- [Weather](https://catalog.data.metro.tokyo.lg.jp/dataset/t000003d0000000151/resource/86f57c1e-d103-4751-aaac-91427499ecb9)  
- [Building feature](https://catalog.data.metro.tokyo.lg.jp/dataset/t131105d0000000058/resource/7ed82057-5d8c-4fc8-a57b-49b4b2d394fd)  
- [Demographic](https://catalog.data.metro.tokyo.lg.jp/dataset/t131105d0000000022/resource/8fe523a7-b478-454f-908c-35b8db3350e2)  
- Behaviour 

Building feature is data for only Meguro City. There is [data](https://catalog.data.metro.tokyo.lg.jp/dataset/t000008d0000000034) for the entire Tokyo, but it should be decided whether one ward is the focus. Data other than weather is user input when it is in service.

## Future Directions
At this stage, the program is intended only for the citizens of Tokyo, however in the future, merging all data into a prediction of district-level energy consumption forecast could be beneficial for government decision making. Furthermore, an even more elaborate data analysis could output sector 3 carbon emissions. 

## Papers 
https://qsel.columbia.edu/assets/uploads/blog/2018/publications/Spatial-Distribution-of-Urban-Building-Energy-Consumption-by-End-Use.pdf 
https://qsel.columbia.edu/assets/uploads/blog/2020/publications/a-scalable-framework-to-measure-the-impact-of-spatial-heterogeneity-on-electrification.pdf
https://arxiv.org/pdf/2005.13180.pdf 
https://arxiv.org/pdf/2207.11953.pdf
https://dspace.mit.edu/bitstream/handle/1721.1/129084/1227274035-MIT.pdf?sequence=1&isAllowed=y 
https://www.mdpi.com/1996-1073/13/10/2497/pdf 
https://fenix.tecnico.ulisboa.pt/downloadFile/1689244997260064/thesis_192316.pdf 
https://www.sciencedirect.com/science/article/pii/S1876610217359520?ref=pdf_download&fr=RR-2&rr=736dd64518beaf5a 
https://openaccess.thecvf.com/content/WACV2022/papers/Fobi_Predicting_Levels_of_Household_Electricity_Consumption_in_Low-Access_Settings_WACV_2022_paper.pdf 
https://arxiv.org/pdf/2207.02589.pdf 
