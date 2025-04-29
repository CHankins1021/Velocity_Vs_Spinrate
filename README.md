# Velocity_Vs_Spinrate
Project Overview

This project analyzes two different groups of MLB pitches to determine which is more effective at generating whiffs (missed swings) and avoiding hits:
	Fastest Pitches – pitches with the highest velocity
	Highest Spinrate Pitches – pitches with the most spin

By comparing the whiff rates and hit rates of each group, we explore whether velocity or spin plays a larger role in pitch effectiveness.

Data Sources

The data was collected from Baseball Savant and split into three CSV files:
	Fastest_Pitches.csv – top 500 fastest pitches
	Highest_Spinrate.csv – top 500 highest-spin pitches

Methodology
	Loaded and cleaned the datasets using Python and Pandas.
	  Calculated:
	    Whiff Rate = Whiffs / Swings
      Hit Rate = Hits / Balls in Play (BIP)
	Plotted bar graphs to visually compare performance.
	Summarized the findings in a table and saved it as velocity_vs_spinrate_summary.csv.

Results

The analysis showed:
	Fastest Pitches - Whiff Rate: 31.04%, Hit Rate: 33.27%
  Spinrate Pitches - Whiff Rate: 31.18%, Hit Rate: 33.15%
	  Hit Rate (Lower is better)
    Whiff Rate (Higher is better)
