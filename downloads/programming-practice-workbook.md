# HVAC Smarty Pants — programming practice workbook

These exercises can begin on paper. Implement them when your actual controllers, firmware, tools and licenses are identified. Each platform has its own blocks, application limits and download procedure.

## Niagara kitControl: fan enable and proof

Sketch occupancy AND enable conditions → fan command. After a start delay, generate a proof-failure condition when command is true and feedback is false.

Predict normal start, failed start, shutdown and manual override/release. Choose trends for occupancy, command, proof and alarm condition. Identify the exact components and their status handling in the installed kitControl palette; the library’s Niagara videos are supporting lessons.

## Honeywell IRM: VAV mode table

List airflow measurement, occupied/unoccupied modes, setpoints, damper demand, overrides and available alarms. Draw mode selection before the airflow-control path.

Predict occupied minimum flow, increased cooling demand, unoccupied operation and invalid airflow measurement. Use the matching IRM block guide and controller template to verify behavior. Record model and tool package before repeating a demonstration.

## Classic Spyder: fan-coil application plan

Record LON or BACnet, controller model and the Classic Spyder tool build. Sketch occupancy, temperature demand, fan enable, valve demand and proof.

Use the Classic guide to identify candidate function blocks and the simulation/debugging workflow. Predict sequence outcomes before opening a matching tool. Keep this plan separate from Model 5/7 IRM demonstrations.

## JCI CCT: airflow loop checkout

Trace measured airflow → error from setpoint → damper demand → actual airflow. Add occupancy and override cases.

Prepare four simulation inputs and predicted outputs. Record actual FX controller family, CCT release and controller package. The library’s first-program CVM video is a Metasys example, so verify applicability before following controller-specific steps.

## Distech EC-gfxProgram: test before download

Write a fan-coil sequence and separate physical points, network values and internal logic. Identify a block you might reuse.

Make a test matrix for occupancy changes, temperature changes, fan failure and override/release. Use the simulator/emulator supported by your actual release; older public feature demos may show different interfaces.

## Shared study record

| Platform / lesson | Prediction | Observed behavior | Explanation | Next test |
| --- | --- | --- | --- | --- |
| | | | | |
| | | | | |
| | | | | |

A useful result is a readable sequence, point list and functional test table. A program that downloads still needs evidence that the equipment responds correctly.
