**Academic Software License: © 2024 UCR (“Institution”).** 
Academic or nonprofit researchers are permitted to use this Software (as defined below) subject to Paragraphs 1-4:
1. Institution hereby grants to you free of charge, so long as you are an academic or nonprofit researcher, a nonexclusive license under Institution’s copyright ownership interest in this software and any derivative works made by you thereof (collectively, the “Software”) to use, copy, and make derivative works of the Software solely for educational or academic research purposes, and to distribute such Software free of charge to other academic or nonprofit researchers for their educational or academic research purposes, in all cases subject to the terms of this Academic Software License. Except as granted herein, all rights are reserved by Institution, including the right to pursue patent protection of the Software.
2. Any distribution of copies of this Software -- including any derivative works made by you thereof -- must include a copy (including the copyright notice above), and be made subject to the terms, of this Academic Software License; failure by you to adhere to the requirements in Paragraphs 1 and 2 will result in immediate termination of the license granted to you pursuant to this Academic Software License effective as of the date you first used the Software.
3. IN NO EVENT WILL INSTITUTION BE LIABLE TO ANY ENTITY OR PERSON FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS SOFTWARE, EVEN IF INSTITUTION HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. INSTITUTION SPECIFICALLY DISCLAIMS ANY AND ALL WARRANTIES, EXPRESS AND IMPLIED, INCLUDING, BUT NOT LIMITED TO, ANY IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE SOFTWARE IS PROVIDED “AS IS.” INSTITUTION HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS OF THIS SOFTWARE.
4. Any academic or scholarly publication arising from the use of this Software or any derivative works thereof will include the following acknowledgment:  The Software used in this research was created by Mst. Shamima Hossain, Boris Baer, Hyoseung Kim, and Vassilis J. Tsotras of UCR. © 2025 CMU Christos Faloutsos.

**Commercial entities: please contact otc@ucr.edu for licensing opportunities.**

# About the Dataset
1. DateTime (hourly): date and time when the data was recorded
2. Temp_Box: Environment Temperature
3. Temp_[hive_no]: Hive Core Temperature
4. Temp_Easy_[hive_no]: Hive's Peripheral Temperature (different than Temp_Box when ice is applied on top)
5. Hum_Box: Environment Humidity
6. Hum_[hive_no]: Hive Core Humidity
7. Hum_Easy_[hive_no]: Hive's Peripheral Humidity
8. Treatment: 0 = no ice; 1 = ice applied

# Publications
1. Mst. Shamima Hossain, Christos Faloutsos, Boris Baer, Hyoseung Kim, and Vassilis J. Tsotras, "Principled Mining, Forecasting and Monitoring of Honeybee Time Series with EBV+" ACM Trans. Knowl. Discov. Data Just Accepted (February 2025). https://doi.org/10.1145/3719014
2. Mst. Shamima Hossain, Christos Faloutsos, Boris Baer, Hyoseung Kim, and Vassilis J. Tsotras, "EBV: Electronic Bee-Veterinarian for Principled Mining and Forecasting of Honeybee Time Series" In Proceedings of the 2024 SIAM International Conference on Data Mining (SDM), Pages 298 - 306, https://doi.org/10.1137/1.9781611978032.34

# Citation

If you use the dataset, please use the following BibTeX to cite our paper. 

@article{10.1145/3719014,\
author = {Hossain, Mst. Shamima and Faloutsos, Christos and Baer, Boris and Kim, Hyoseung and Tsotras, Vassilis J.},\
title = {Principled Mining, Forecasting and Monitoring of Honeybee Time Series with EBV+},
year = {2025},\
publisher = {Association for Computing Machinery},\
address = {New York, NY, USA},\
issn = {1556-4681},\
url = {https://doi.org/10.1145/3719014},\
doi = {10.1145/3719014},\
abstract = {Honeybees, as natural crop pollinators, play a significant role in biodiversity and food production for human civilization. Bees actively regulate hive temperature (homeostasis) to maintain a colony’s proper functionality. Deviations from usual thermoregulation behavior due to external stressors (e.g., extreme environmental temperature, parasites, pesticide exposure, etc.) indicate an impending colony collapse. Anticipating such threats by forecasting hive temperature and finding changes in temperature patterns would allow beekeepers to take early preventive measures and avoid critical issues. In that case, how can we model bees’ thermoregulation behavior for an interpretable and effective hive monitoring system?In this paper, we propose the principled EBV + (Electronic Bee-Veterinarian plus) method based on the thermal diffusion equation and a novel ‘sigmoid’ feedback-loop (P) controller for analyzing hive health with the following properties: (i) it is effective on multiple, real-world beehive time sequences (recorded and streaming), (ii) it is explainable with only a few parameters (e.g., hive health factor) that beekeepers can easily quantify and trust, (iii) it issues proactive alerts to beekeepers before any potential issue affecting homeostasis becomes detrimental, and (iv) it is scalable with a time complexity of O(t) for reconstructing and O(t\texttimes{}m) for finding cuts of a sequence with C time-ticks. Experimental results on multiple real-world time sequences showcase the potential and practical feasibility of EBV+. Our method yields accurate forecasting (up to 72\% improvement in RMSE) with up to 600 times fewer parameters compared to baselines (ARX, seasonal ARX, Holt-winters, and DeepAR), as well as detects discontinuities and raises alerts that coincide with domain experts’ opinions. Moreover, EBV+ is scalable and fast, taking less than 1 minute on a stock laptop to reconstruct two months of sensor data.},\
note = {Just Accepted},\
journal = {ACM Trans. Knowl. Discov. Data},\
month = feb,\
keywords = {Honeybees, Forecasting, Event-detection}\
}
