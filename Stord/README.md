# STORD Network Optimization Exercise
The goal of this exercise is to provide a consulting driven solution to a supply chain network optimization problem. This challenge is set up as case study similar to situations we deal with at STORD. It is intentionally left open-ended because quite often we are in situations where our clients aren't aware of bottlenecks in their network and it is our job to discover areas for improvement using their data.

# The Case
Our fictional client (Bread Inc.) is a baked goods manufacturing company with headquarters in Mexico. Bread Inc. must strive to meet daily consumer demand for fresh bakery products on the shelves of over 1 million stores along its 45,000 routes across Mexico. Currently, daily inventory calculations are performed by direct delivery sales employees who must single-handedly predict the forces of supply, demand, and hunger based on their personal experiences with each store. With some breads carrying a one week shelf life, the acceptable margin for error is small.

The dataset you are given consists of 9 weeks of sales transactions in Mexico. Every week, there are delivery trucks that deliver products to the vendors. Each transaction consists of sales and returns. Returns are the products that are unsold and expired.

Our stakeholders aren't well equipped with analytical capabilities within their organization, they are relying on us to help them assess their current proccesses and identify bottlenecks.

We're asking you to dig into their data come up with valuable statistical insights and trends. Get creative and identify bottlenecks in their current supply chain networks. Additionally, structure your deliverable in a succinct and well storylined manner to ensure an easy to understand and engaging flow.

# The Data
You can download the data from here

Things to note:

There are duplicate Cliente_ID's in cliente_tabla, which means one Cliente_ID may have multiple NombreCliente that are very similar. This is due to the NombreCliente being noisy and not standardized in the raw data, so it is up to you to decide how to clean up and use this information.
### File descriptions
- data.csv — all sales transactions
- cliente_tabla.csv — client names (can be joined with data on Cliente_ID)
- producto_tabla.csv — product names (can be joined with data on Producto_ID)
- town_state.csv — town and state (can be joined with data on Agencia_ID)
### Data fields
- Semana — Week number (From Thursday to Wednesday)
- Agencia_ID — Sales Depot ID
- Canal_ID — Sales Channel ID
- Ruta_SAK — Route ID (Several routes = Sales Depot)
- Cliente_ID — Client ID
- NombreCliente — Client name
- Producto_ID — Product ID
- NombreProducto — Product Name
- Venta_uni_hoy — Sales unit this week (integer)
- Venta_hoy — Sales this week (unit: pesos)
- Dev_uni_proxima — Returns unit next week (integer)
- Dev_proxima — Returns next week (unit: pesos)

# Deliverable
Implement your solution as a script in python (Ipython notebooks are preferred)
Define a new aggregated field in the dataset for your definition of product demand.
Create a 5 min presentation with your choice of graphs and content that tell a succinct story (optional)
Email the point of contact that sent you this exercise.
Include your Ipython notebook with all relevant statistical graphs
Make sure to label all graphs and add comments where needed
Be prepared to walk through your solution during the on-site interview.

# Evaluation
Your submission will be evaluated along the following criteria by the Reviewer

Completeness - Does your submission meet the Deliverables specified above?
Business Acumen - How easy was it for a business stakeholder (with limited technical knowledge) to understand your solution?
Storylining - Evaluate the flow of your solution
Creativity - Evaluate your ability to tease out non-obvious insights from the data
Technical Capability - How statistically reliable are your insights?
Critical Thinking - Please be ready to speak to your thinking proccess for the solution here.
Notes:
The good news is that we will not subject you to a code exercise on a whiteboard when you are on-site!
Please feel free to ask clarifying questions via email!
Thank you for the time you are spending as a candidate with STORD!
