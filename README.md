# Week_11

– “Disclaimer: [Chat-GPT] was/were used to complete
HW #[2].[A & B] to [Complete code, find cause for errors obtained when writing code, optimize code, understand the results, and for comparison].”


#Name: Covenant Adenuga
#Contact: cadenug@emory.edu

## Question Addressed
I chose to answer question 2.

## Key Insights

1. **Infection Peaks and Healthcare Capacity**:
   - Stricter social distancing measures (lower movement probabilities) significantly reduce the peak number of infections, thereby lowering the risk of healthcare system overload.
   - Higher movement probabilities (representing relaxed distancing) lead to faster infection spread, with higher peaks and shorter pandemic durations.

2. **Timing of Infection Peaks and Spread Duration**:
   - Reduced movement probabilities delay the timing of infection peaks, allowing infections to spread more gradually. The flattened curve spreads cases over a longer period, helping healthcare systems manage ongoing cases more effectively.
   - While stricter distancing extends the duration of the pandemic, it distributes the infection load more evenly, avoiding overwhelming healthcare resources at any single point in time.

3. **Effectiveness of Social Distancing**:
   - The results show that while social distancing may not significantly lower the total number of infections over the pandemic, it controls the spread rate. This flattened infection curve is crucial in avoiding healthcare saturation.


## Comparative Model Performance

- **Without Social Distancing**: High and early infection peaks, with infections spreading rapidly through the population. Shorter pandemic duration but intense healthcare demand in a short period.
- **With Social Distancing**: Lower infection peaks and a more gradual increase and decrease in infection counts. Pandemic duration extends, but healthcare demand is manageable, showing the value of distancing in pandemic management.

This agent-based model demonstrates foundational principles in model-based machine learning, where:
- **Modeling Assumptions** (like agent behaviors, infection probabilities, and recovery rates) are encoded explicitly and tested to see their effects on observed outcomes.
- **Parameter Sensitivity**: We systematically vary parameters (e.g., movement probability, infection rate, recovery rate) to assess the robustness of the model and understand the interaction between these parameters and model performance.
- **Behavioral Dynamics**: Incorporating real-world behaviors (like social distancing and avoidance) provides insights into how individual actions aggregate to population-level patterns. Such models are vital in understanding complex, dynamic systems like pandemics and informing data-driven policy decisions.

## Suggestions for Future Modeling Improvements

1. **Heterogeneous Population Groups**: Future models could include agents with different levels of vulnerability (e.g., age groups or comorbidities) to see how targeted interventions impact outcomes.
   
2. **Additional Interventions**: Adding interventions such as vaccination, quarantine measures, and testing could improve realism and provide insights into combined intervention strategies.

3. **Improved Spatial Awareness**: Enhancing agents’ spatial awareness to dynamically adjust social distancing based on real-time infection proximity could lead to more nuanced infection dynamics, capturing adaptive human behaviors during pandemics.

4. **Machine Learning Enhancements**: Incorporating machine learning techniques to optimize parameter settings based on observed infection trends could provide a framework for adaptive policy-making in real-time.

This project highlights the potential of agent-based models as tools for pandemic management and underscores the importance of thoughtful modeling choices in understanding and influencing complex systems.
