![Project Logo or Screenshot](images/Logo.png)

# VivaSTGNNs

## 🚩 Problem
Currently, onboard sales suffer due to unpredictable demand and inefficient inventory management. The objective is to develop a model that accurately predicts product demand during flights based on historical data and real-time factors.

## 📄 Description

Our project leverages multinodal graph neural networks to model a dynamic transportation system involving airships and cities. In this system, we have two primary types of nodes:

### Airships
Airships represent unique flight IDs within our network. Each airship node contains several characteristics, including:
- Max capacity for passengers or cargo
- Number of sales for each sold product

### Cities
Cities serve as nodes connected to airships but not to other airships directly. Each city node includes:
- City type (e.g., metropolitan, suburban, rural)

In our network, airships can be connected to multiple cities simultaneously, but only two connections are active at any given time. This active connection signifies an ongoing flight between the airship and the connected cities. 

When a flight arrives at its destination city:
- The actual sales of products onboard are compared to the predicted sales.

Our multinodal graph neural network architecture captures the interdependencies and interactions between airships and cities, enabling dynamic modeling of flight operations and product sales predictions within this transportation system.

This model allows for real-time analysis and prediction of transportation logistics and product demand across interconnected airships and cities, providing valuable insights for optimizing flight operations and inventory management.
