---
author: "Akilan Selvacoumar"
date: 2020-08-20
title: AreWeFastYet(Vitess)
---

The purpose of this project is to do a benchmark run when ever there is a push. The background activity is fairly simple, we create our own bare metal server. Once this server is created we run a bunch of ansibles(for sysbench) and once the run is complete we read the results and store them in a mysql instance. Once the following operations are complete we take down the server.

Uses sysbench to run a benchmark on vitess. The following codebase:

    - Creates a VPS
    - Runs the ansibles on the VPS
    - Reads results from the VPS and stores in the database
    - Kills the VPS

## Index
1. [Installation](https://github.com/vitessio/arewefastyet/blob/master/docs/Installation.md)
2. [Api](https://github.com/vitessio/arewefastyet/blob/master/docs/Api.md)
3. [Cli](https://github.com/vitessio/arewefastyet/blob/master/docs/cli.md)
4. [Makefile](https://github.com/vitessio/arewefastyet/blob/master/docs/Makefile.md)

### Upcoming Talk: 
https://kccnceu2021.sched.com/event/iaAj

Languages used: Go , Python 

Repository: https://github.com/vitessio/arewefastyet/
