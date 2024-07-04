ServiceNow Customer Service

sn_customerservice_case







Issues:
Duplicates

User 'u_customer_facing_status' to replace 'state'
- assigned_count
- u_customer_update_count


Delta Load Setting
  Step 1: Parameter
    Type：           Dynamic
    Table:
    Column:         (updated/chagned date)
    Operation type: FIND_MAX
    Date type:       Date
    Vlaues
  Statement: AEDAT >= <%ParameterDate%> or CPUDT >=<%ParameterDate%>
