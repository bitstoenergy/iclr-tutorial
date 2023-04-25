# Smart Meter Data Analytics: Practical Use-Cases and Best Practices of Machine Learning Applications for Energy Data in the Residential Sector

### **Authors:**
- **Tobias Brudermüller (Brudermueller)**, Bits to Energy Lab, ETH Zurich, tbrudermuell@ethz.ch
- **Markus Kreft**, Bits to Energy Lab, ETH Zurich, mkreft@ethz.ch

### **Supervisors:**
- **Prof. Dr. Elgar Fleisch**, Bits to Energy Lab, ETH Zurich & University of St. Gallen
- **Prof. Dr. Thorsten Staake**, Bits to Energy Lab, ETH Zurich & University of Bamberg

### **Description:**
- Practical tutorial for the **11th International Conference on Learning Representations (ICLR 2023)**
- Part of the [**ICLR 2023 Workshop: Tackling Climate Change with Machine Learning**](https://www.climatechange.ai/events/iclr2023)
- Hosted by [**Climate Change AI**](https://www.climatechange.ai/)
- **Execute the tutorial via Google Colab** by using [this link](https://colab.research.google.com/github/bitstoenergy/iclr-tutorial/blob/main/SmartMeterDataAnalytics_Tutorial.ipynb)!

### **Key Learning Objectives**
In this tutorial, we provide a practical guide to current trends in smart meter data analytics. In particular, we focus on feature engineering and machine learning scenarios for energy data. During this tutorial:

- You will gain insights into current trends and use cases in the energy space. 
- You will learn best practices for energy data visualization. 
- You will apply both machine learning approaches and data mining techniques to real-world energy data.
- You will get a sense of typical and atypical energy use in a residential building.

In addition, some concepts offer the possibility of being applied to other time series data outside of the energy domain. 

**Note:** We would also like to point out that some utilities allow their customers access to their own smart meter data either through customer portals or upon request. If you have an active smart meter at home, you can use this guide as a starting point for analyzing your own energy usage.

### **Abstract:** 
To cope with climate change, the energy system is undergoing a massive transformation. Due to the electrification of all sectors, the power grid is facing high additional demand. As a result, the digitization of the grid is increasingly gaining attention. The smart grid relies heavily on the increasing deployment of smart meters around the world. The corresponding smart meter data is typically a time series of power or energy measurements with a resolution between 1 s and 60 min. This data provides valuable insights and opportunities for monitoring and controlling activities on the power grid. 

In this tutorial, we therefore provide an overview of best practices for analyzing smart meter data. We focus on machine learning applications and low resolution (15 min) energy data in a residential setting. We use only real-world data and cover use cases that are highly relevant to practical applications. Although this tutorial is specifically tailored for an energy audience, we believe that anyone in the data analytics and machine learning field can benefit from it, as many techniques are applicable to all time series data. Through our tutorial, we hope to foster new ideas, contribute to interdisciplinary exchange between different research fields, and educate people about energy use.

### **Target Audience:** 
In the best case, you have already worked with Python and have some basic knowledge of machine learning. Nevertheless, this tutorial can be completed and understood by anyone with basic programming skills. 

- If you are a **student**, this tutorial will provide you with a practical introduction to applying machine learning to time series data. 
- If you are a **researcher in machine learning**, you can use this tutorial to find ideas for your research and potential data sets for benchmarking. 
- If you work for a **utility**, this tutorial will provide you with an overview of practical use cases and the current state of the art in smart meter data analytics.
- If you are an **individual** interested in energy-related topics, you can learn more about smart grid applications and energy consumption in this tutorial.

### **Outline**

**1. Introduction to smart meter data**
  1. What is smart meter data?
  2. Relevance for tackling climate change
  3. Chances and limitations
  4. Power vs. energy measurements
  5. Data resolution
  6. Data availability
  7. Contextual information and domain knowledge
  7. Making use of additional data sources

**2. Preparations for this tutorial**
  1. Importing packages
  2. Importing the data

**3. Best practices for visualizing smart meter data**
  1. Time-series visualizations of energy data
  2. Visualizing distributions of energy consumption
  3. Multi-dimensional visualizations
  4. Annotating visualizations with additional context information
  5. Displaying aggregated demand

**4. Pre-processing smart meter data**
  1. Combining smart meter data with temperature data
  2. Add additional information for filtering timestamps
  3. Normalization methods
  4. Interpolation methods and downsampling
  5. Outlier detection with Hampel filter
  6. Simple baseload estimation
  7. Enhancing small activities
  8. Detecting switching activities
  9. Sliding window approaches
  10. Feature extraction
  11. Detecting peaks in distribution
  12. Frequency-based methods for low-resolution data

**5. Non-Intrusive Load Monitoring (NILM) / Load Disaggregation**
  1. Using classification algorithms to detect appliance installations
  2. Applying simple deep learning models for NILM
  3. Applying Hidden Markov Models for NILM
  4. Correctly evaluating NILM approaches
  5. Rule-based heuristics for pattern isolations


**6. Flexibility Estimation**
  1. Estimating load shifting potential of disaggregated appliances

**7. Anomaly Detection**
  1. Introduction to online vs. offline change point detection
  2. Finding state changes with offline change point detection
  3. Finding anomalies with sliding window
  4. Applying Symbolic Aggregate ApproXimation
  5. Finding discords and motifs

**8. Customer segmentation**
  1. Extraction of energy signatures through regression
  2. Extraction of average day profiles
  3. Applying clustering algorithms

**9. Load Forecasting**
  1. Brief and short introduction (*as the topic has already been covered in previous CCAI-tutorial*)

**10. Conclusion**

**11. Additional Resources**
  1. Data Sets
  2. Software Packages
  3. Other

**12. References**
