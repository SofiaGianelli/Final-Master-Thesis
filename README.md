# Final-Master-Thesis

This master ’s thesis aims to perform Support Vector Machine (SVM) regression for
forecasting daily peak electricity load in the New England region. The complexity of
predicting peak demand is the interaction between several factors, particularly weather
conditions. Using hourly demand data from 2015 to 2023, the study investigates the
relationship between temperature and electricity demand across eight load zones, plus the
total of New England, and each station is linked to a corresponding weather station.

To address the limitation of uncertainty in future temperature, temperature scenarios
were generated using K-Means clustering. These scenarios were then used in to predict
the trained SVR models to enhance the robustness. The models were evaluated based on
Mean Squared Error (MSE) and Brier Score, with the results compared with three naive
forecasting models: Naive24, Naive168, and a Mixed Naive approach.

The findings show that SVR models perform well in most regions, with the scenariobased approach further improving accuracy. Southeastern Massachusetts and Rhode Island exhibited the lowest prediction errors, while regions like Maine proved to be more
challenging due to their unique temperature and demand profiles.
