Our fictional client (Bread Inc.) is a baked goods manufacturing company with headquarters in Mexico. Bread Inc. must strive to meet daily consumer demand for fresh bakery products on the shelves of over 1 million stores along its 45,000 routes across Mexico. Currently, daily inventory calculations are performed by direct delivery sales employees who must single-handedly predict the forces of supply, demand, and hunger based on their personal experiences with each store. With some breads carrying a one week shelf life, the acceptable margin for error is small.

The dataset consists of 9 weeks of sales transactions in Mexico. Every week, there are delivery trucks that deliver products to the vendors. Each transaction consists of sales and returns. Returns are the products that are unsold and expired.

We are asked to assess their current proccesses and identify bottlenecks, dig into their data to come up with valuable statistical insights and trends.

File descriptions: 
--> data.csv — all sales transactions
--> cliente_tabla.csv — client names (can be joined with data on Cliente_ID)
--> producto_tabla.csv — product names (can be joined with data on Producto_ID)
--> town_state.csv — town and state (can be joined with data on Agencia_ID)

Data fields:
--> Semana — Week number (From Thursday to Wednesday)
--> Agencia_ID — Sales Depot ID
--> Canal_ID — Sales Channel ID
--> Ruta_SAK — Route ID (Several routes = Sales Depot)
--> Cliente_ID — Client ID
--> NombreCliente — Client name
--> Producto_ID — Product ID
--> NombreProducto — Product Name
--> Venta_uni_hoy — Sales unit this week (integer)
--> Venta_hoy — Sales this week (unit: pesos)
--> Dev_uni_proxima — Returns unit next week (integer)
--> Dev_proxima — Returns next week (unit: pesos)