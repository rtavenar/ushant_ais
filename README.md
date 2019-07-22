# Ushant AIS

This repository is about "Ushant AIS", a dataset of vessel trajectories recorded using AIS in the Ushant region.

## In more details

This dataset corresponds to 6 months of AIS data of vessels steaming in the area of the Ushant traffic separation scheme (in Brittany, West of France).
This is an area with one of the  highest traffic density in the world, with a clear separation scheme with two navigation lanes.
Different kinds of vessels are present in the area, from cargos and tankers with high velocity and straight routes to sailing boats or fishing vessels with low speed and different sailing directions.
As such, the area is highly monitored to avoid collision or grounding, and a better analysis and understanding of the different ship behaviors is of prime importance.

The whole trajectory data set consists in 18,603 trajectories, gathering overall more than 7 millions GPS observations.
Only trajectories having more than 30 points were kept, time lag between two consecutive observations ranges between 5 seconds and 15 hours, with 95% of time lags below 3 minutes.

## Link

The dataset is available on figshare there:
<https://figshare.com/articles/Ushant_AIS_dataset/8966273>

## Reference

Also, if you use this dataset for research, please cite:

```
@article{gloaguen_ais,
  title = "Scalable clustering of segmented trajectories within a continuous time framework: application to maritime traffic data",
  author = "Pierre Gloaguen and Laetitia Chapel and Chlo{'e} Friguet and Romain Tavenard"
}
```

## Acknowledgements

Authors would like to thank CLS and Erwan Guegueniat for providing the raw data that allowed building this dataset.
This work has been supported by DGA through the ANR/Astrid SESAME project (ref: ANR-16-ASTR-0026).
