#Nodal Analysis of a Hydrocarbon Production System

📌 Project Overview:

This project performs Nodal Analysis for a hydrocarbon well system. The goal is to optimize production by finding the operating point where the Inflow Performance Relationship (IPR) and Tubing Performance Relationship (TPR) curves intersect. This intersection represents the most efficient flow rate (q) and bottom-hole flowing pressure (Pwf) for various tubing sizes. This project shows sensitivity of reservoir to GOR,skin and watercut.

🧪 Key Features:

Generates IPR curve using Vogel's equation (for solution gas drive).

Calculates TPR curves for multiple tubing diameters.

Plots the IPR and TPR curves together to identify the optimal production point.

Uses real-time simulation data with adjustable well and reservoir parameters.

Provides graphical visualization using Matplotlib for analysis

📚 Reference Equations:

IPR (Vogel’s Equation):  
q/q_max = 1-0.2(Pwf/Pr)-0.8(Pwf/Pr)^2

TPR: Calculated using empirical pressure drop formulas accounting for tubing ID, friction, and fluid properties.

Author:

Vishakha Khatri

Petroleum Engineering Student

IIT (ISM) Dhanbad

khatrivishakha1185@gmail.com
