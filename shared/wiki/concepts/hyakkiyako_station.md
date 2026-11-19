---
name: Hyakkiyako Station
summary: "Northwestern Line station with a temple-gate roof: D.U. and Shanhaijing every 15 minutes, and the hourly tunnel train north; 05:30–23:30."
known:
  hyakkiyako_school: knows
backdrop: train-station
place_id: hyakkiyako_station
connections:
  - to: hyakkiyako_district
    ways:
      - by: walk
        minutes: 5
    note: Out through the lantern gate.
  - to: shanhaijing_station
    ways:
      - by: train
        minutes: 18
    note: Northwestern Line. Times include the average wait.
  - to: ebisu_station
    ways:
      - by: train
        minutes: 45
    note: Hyakkiyako North Line, through the long tunnel, hourly. Times include the average wait.
map:
  x: 1.1
  y: 1.08
---

# Hyakkiyako Station

A station dressed as a temple gate, with lanterns hung over the platforms and
tour guides waving flags at the exit, which leads out into
[[hyakkiyako_district|Hyakkiyako]]'s streets. Northwestern Line trains run to
D.U. Central and [[shanhaijing_station|Shanhaijing]]; once an hour the North
Line train leaves through the long tunnel for [[ebisu_station|Ebisu]].
