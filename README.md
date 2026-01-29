# Diode Temperature Analysis (25 °C vs 75 °C)

## Overview
The same diode circuit was simulated in LTspice at two different temperatures: 25 °C and 75 °C. A DC sweep was used in both cases to observe how temperature affects the diode’s electrical behavior.

## Effect on Forward Voltage
When the temperature increases from 25 °C to 75 °C, the forward voltage of the diode decreases. At higher temperature, the diode begins to conduct at a lower voltage. This happens because increased temperature provides more energy to charge carriers, making it easier for current to flow through the PN junction.

## Effect on Reverse Current
The reverse current of the diode increases significantly at higher temperature. At 75 °C, the leakage current is noticeably larger than at 25 °C. This is caused by increased thermal generation of charge carriers inside the diode.

## Why Temperature Affects Diode Behavior
Diodes are semiconductor devices, and semiconductor properties depend strongly on temperature. As temperature rises, carrier mobility and carrier concentration increase, which affects both forward conduction and reverse leakage.

## Why This Matters in Real Electronic Systems
Temperature effects are important because they can change circuit performance and reliability. Lower forward voltage can alter bias points, and increased reverse current can lead to higher power dissipation and thermal runaway. Designers must consider temperature effects to ensure circuits work correctly under different operating conditions.
