# DataX

- Drag in the toolbar<img src="/img/datax.png" width="35"/>Task node into the drawing board

  <p align="center">
   <img src="/img/datax-en.png" width="80%" />
  </p>

- Custom template: When you turn on the custom template switch, you can customize the content of the json configuration file of the datax node (applicable when the control configuration does not meet the requirements)
- Data source: select the data source to extract the data
- sql statement: the sql statement used to extract data from the target database, the sql query column name is automatically parsed when the node is executed, and mapped to the target table synchronization column name. When the source table and target table column names are inconsistent, they can be converted by column alias (as)
- Target library: select the target library for data synchronization
- Target table: the name of the target table for data synchronization
- Pre-sql: Pre-sql is executed before the sql statement (executed by the target library).
- Post-sql: Post-sql is executed after the sql statement (executed by the target library).
- json: json configuration file for datax synchronization
- Custom parameters: SQL task type, and stored procedure is a custom parameter order to set values for the method. The custom parameter type and data type are the same as the stored procedure task type. The difference is that the SQL task type custom parameter will replace the \${variable} in the SQL statement.
