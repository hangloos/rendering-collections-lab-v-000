<h1>Invoices</h1>
<table>
  <tr>
    <th>Invoice Id
    <th>Customer</th>  
  </tr>

<%= render :partial => "/invoices/invoice", :collection => @invoices %>

</table>