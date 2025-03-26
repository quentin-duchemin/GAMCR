Presentation of the project
---------------------------



Challenge
~~~~~~~~~

Rivers often react quickly to rainfall events and can cause water quantity problems like floods. While the timing of watershed responses is key to our understanding of flood generation, quantifying these responses is complex because they can be nonlinear, time-variable and may take irregular shapes that are difficult to predict a priori. Most of existing methodologies typically rely on strong assumptions (e.g., stationarity) and on models that are calibrated against data but not yet data-driven. 


Description of the method
~~~~~~~~~~~~~~~~~~~~~~~~~

We introduce a new knowledge-guided but data-driven methodology to estimate the response functions of watershed to rainfall events. Our model relies on Generalized Additive Models (GAMs) with features encoding: 

- the intensity of the precipitation event

- information describing the catchment condition induced by past events such as weighted sum of past precipitation and potential evapotranspiration. 

One can easily add additional features to our model. A typical example is the cosine and sine of the time from January 1st to allow the model to estimate a seasonality pattern. Another example is a time variable allowing the model to learn potential change over time of the catchment behaviour.

Applications of the method
~~~~~~~~~~~~~~~~~~~~~~~~~~

Once trained on a given site for which at least precipitation and streamflow time series are available, one can predict the transfer function corresponding to any new precipitation event. Therefore, our model paves the way to many application to draw hydroglogical insights on the way different catchments behave. 
