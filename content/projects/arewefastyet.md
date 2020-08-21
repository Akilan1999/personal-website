---
author: "Akilan Selvacoumar"
date: 2020-08-20
title: AreWeFastYet(Vitess)
---

The purpose of this project to run a bunch on Ansibles as a benchmark for the project called Vitess. All the benchmark results are stored in
a MySql database. The benchmark runs can be set as scheduler or on Api call.

Uses sysbench to run a benchmark on vitess. The following codebase:

    - Creates a VPS
    - Runs the ansibles on the VPS
    - Reads results from the VPS and stores in the database
    - Kills the VPS


 Scripting Language: Python

 Repository: https://github.com/vitessio/arewefastyet/
